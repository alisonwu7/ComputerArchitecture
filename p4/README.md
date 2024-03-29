# Project 4: Longan Nano minigame

This repo contains the framework code for your Project 4. 

In this project, you will be implementing a Pong game using the Longan Nano development board we've given to you. We've provided you a framework here.

You can also choose to implement your own minigame.

We hope this project will help you experience programming RISC-V on a real machine rather than in a simulator.

For full details of this project, please see course website[Project 4 - Computer Architecture I - ShanghaiTech University](https://robotics.shanghaitech.edu.cn/courses/ca/22s/projects/4/)

## PLEASE READ

The projects are part of your design project worth 2 credit points. As such they run in parallel to the actual course. So be aware that the due date for project and homework might be very close to each other! Start early and do not procrastinate.

## Download Framework

Download the framework from gitlab and Check if you already have the following files after pulling.

```
.
├── LICENSE
├── Makefile
├── README.md
├── dfu-util
├── include
│   ├── README
│   ├── fatfs
│   │   ├── diskio.h
│   │   ├── ff.h
│   │   ├── ffconf.h
│   │   └── tf_card.h
│   ├── gd32v_pjt_include.h
│   ├── gd32vf103_libopt.h
│   ├── lcd
│   │   ├── bmp.h
│   │   ├── lcd.h
│   │   └── oledfont.h
│   ├── systick.h
│   └── utils.h
├── platformio.ini
└── src
    ├── assembly
    │   └── example.S
    ├── fatfs
    │   ├── 00history.txt
    │   ├── 00readme.txt
    │   ├── ff.c
    │   ├── ffsystem.c
    │   ├── ffunicode.c
    │   └── tf_card.c
    ├── lcd
    │   └── lcd.c
    ├── main.c
    ├── systick.c
    └── utils.c
```
