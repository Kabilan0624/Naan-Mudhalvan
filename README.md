Virtual Cinema Platform - Deployment Guide

Welcome to the deployment guide for the Virtual Cinema Platform. In this document, we will provide step-by-step instructions on how to deploy this platform using IBM Cloud Static Web Apps. You'll also find information on how to navigate the platform, upload videos, and manage dependencies.

Table of Contents

  *Prerequisites
  *Deployment Instructions
  *Navigating the Platform
  *Uploading Videos
  *Managing Dependencies


Before you begin, make sure you have the following prerequisites:

An IBM Cloud account (You can sign up at IBM Cloud)
A local copy of the platform's source code.
An IBM Cloud Video Streaming account.
Deployment Instructions

IBM Cloud Account:

If you don't have an IBM Cloud account, sign up for one.

Install the IBM Cloud CLI:

Install the IBM Cloud CLI on your local machine.

Login to IBM Cloud:

Open a terminal and run ibmcloud login to log in to your IBM Cloud account.

Change Directory:

Navigate to the directory containing your platform's source code.

  Create a Static Web App:

  ibmcloud app deploy

  Access Your Platform:

Once the deployment is complete, you can access your platform by running:

ibmcloud app show virtual-cinema-platform
Navigating the Platform

The platform consists of the following pages:

Home: An introduction to the platform.
categories: Which type od videp categorie.
Watch: A page for watching a specific video.
Upload: A page for uploading videos.
Use the navigation menu to switch between pages.

Uploading Videos

To upload a video, follow these steps:

Go to the Upload page.
Click the "Choose File" button and select the video file you want to upload.
Click the "Upload" button.
The platform will upload the video file and make it available for streaming.

Managing Dependencies

The platform uses the following dependencies:

 * IBM Cloud Video Streaming SDK
 * Flask

Make sure all dependencies are installed before deployment.
