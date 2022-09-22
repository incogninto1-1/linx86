# Linx86
LinX86 is a bare-bones GNU/Linux operating system with the purpose of being fast, non-bloated, universal and simple to understand how it works.
It is still a work in progress operating system but so far the build is broken.
The issue seems to be my custom init system called Duct Tape init because it is meant to serve as a basic substitiude until I get OpenRC or a different init system working on it.
Speaking of the custom init system it is very basic consisting of only a few lines of shell code. I made it because I stll have to figure out how to use OpenRC and/or communicate with the kernel via C++.
If people want me to keep Duct Tape init I will try to maintain it otherwise I will probably get rid of it.
The package manager is the demo package manager that I have on https://github.com/incogninto1-1/GCEI.
But for short it is written in C++ and the concept does exactly what it says. It grabs the packages, checks them, extracts and installs them.
This project still has a lot to go by but hopefully it is going to do well.
If you want to contact me or help me out send me an email at incogninto123(at)gmail(dot)com
