==================
Image Segmentation 
==================

This tutorial is on image segmentation and image data post-processing.  The objectives are to gain a basic understanding of the different types of images frequently acquired from medical devices.  Understand some of the DICOM standard and the information that is useful to us.  Manual and semi-automatic image segmentation and segmented data post-processing.

Overview
======== 

The Types of images that we come across can be roughly divided into two groups macroscopic anatomical images and microscopic anatomical images.  The macroscopic image modalities that we typically come across are Magnetic Resonance Images (MRI), Computed Tomography (CT) images and Ultrasound (US).  The microscopic images that we use are confocal images.

Most medical devices store their image output using the the Digital Imaging and Communications in Medicine (DICOM) standard.  The DICOM standard is a standard that covers the handling, storing, printing and transmitting of information in medical imaging.  It includes a file format definition and a network protocol definition.  We shall look at the information that can be stored in the DICOM file format and look at how we can make use of it.

Task One
========

Task one is to investigate the DICOM headers from a set of images stored using the the.com standard.  It is quite common to seeTheDICOM standardUsed interchangeably withDICOM image Format.

  