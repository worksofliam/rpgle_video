### Intro

Hello and welcome to the IBM i and RPGLE introduction video. This video will cover the basics of using RPGLE and will not nessacerily cover all IBM i topics. This is due to the nature of how much there would be to learn on the way.

We will be covering a range of topics. To start, we'll look at

* environment setup,
* development environment setup,
* and then specific RPG topics.

We will not be looking into the history of IBM i or RPGLE. We'll only be covering newer and modern topics, which include total-free format RPGLE and embedded SQL and service programs.

## Environment setup

This video will not cover setup or installation of any tools on IBM i. I do suggest you ask you system admin to help get some of these, though none of them are required. If you're using PUB400, I do expect most of these tools to be available on there. If you're looking to install them yourself, you can find them through yum.

You will need:

* A user profile to sign on with,
* SSH daemon started on your IBM i, which PUB400 should already have enabled
* A library that you can manage objects in,
* and a source file inside of that library, though we will be creating one.

You can optionally install:

* tn5250, which is available through yum,
* or if you can't get tn5250, you need to install Access Client Solutions, also referred to as ACS, from the IBM website,
* and db2util, which is available through yum

## Development environment setup

The development environment is the easiest to setup. Throughout this video, we will be using Visual Studio Code, a free and open-source IDE created by Microsoft. It has all of the tools needed for development on IBM i.

* First off, you will want to download and install VS Code from it's website.
* Following the installation, you will want to install the IBM i Development Pack extension from the VS Code Marketplace 

### Connecting to your system

