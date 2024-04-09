cmake_minimum_required(VERSION 3.27)
project(SENG1210_Prison_Database)

set(CMAKE_CXX_STANDARD 14)

include_directories(V4)

add_executable(SENG1210_Prison_Database
        V4/output/WelcomePage.dSYM/Contents/Resources/DWARF/WelcomePage
        V4/output/WelcomePage.dSYM/Contents/Resources/Relocations/aarch64/WelcomePage.yml
        V4/output/WelcomePage.dSYM/Contents/Info.plist
        V4/output/WelcomePageWithSchedule.dSYM/Contents/Resources/Relocations/aarch64/WelcomePageWithSchedule.yml
        V4/output/WelcomePageWithSchedule.dSYM/Contents/Info.plist
        V4/output/blockInfo.txt
        V4/output/Customize
        V4/output/schedule.txt
        V4/output/V4_Staff
        V4/output/V4_User
        V4/Customize.h
        V4/EntryException.h
        V4/FileNoOpenException.h
        V4/PasswordException.h
        V4/RangeException.h
        V4/schedule.cpp
        V4/V4_Inmate.cpp
        V4/V4_Inmate.h
        V4/V4_Staff.cpp
        V4/V4_Staff.h
        V4/V4_Test.cpp
        V4/V4_User.cpp
        V4/V4_User.h
        V4/WelcomePage.cpp)
