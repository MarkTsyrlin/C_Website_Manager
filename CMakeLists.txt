cmake_minimum_required(VERSION 3.27)
project(WebsiteManager C)

set(CMAKE_C_STANDARD 11)

add_executable(WebsiteManager Candidate.c
        Candidate.h
        Client.c
        Client.h
        Company.c
        Company.h
        CompanyBinaryFile.c
        CompanyBinaryFile.h
        CompanyTextFile.c
        CompanyTextFile.h
        Contact.c
        Contact.h
        Date.c
        Date.h
        def.h
        Feedback.c
        Feedback.h
        General.c
        General.h
        List.c
        List.h
        Macros.h
        cmake-build-debug/main.c
        Payment.c
        Payment.h
        Project.c
        Project.h
        projectManagement.c
        projectManagement.h
        Task.c
        Task.h
        TeamMember.c
        TeamMember.h)
