---
Description: '.'
ms.assetid: '1fa34b69-ae34-40e5-b71a-cb9c74f3fc3a'
title: Assessment Execution Engine
---

# Assessment Execution Engine

## Purpose

The Assessment Execution Engine (AXE) enables the management and execution of Windows system assessments. Assessments can help a person understand the state of a system and remedy problems with performance, reliability, or functionality. AXE provides infrastructure needed to manage assessments using a UX tool or script, run assessments, make measurements, process raw data into results, run diagnostics, and publish the results.

## Developer audience

This documentation is intended for software developers who want to write assessments or solutions that use the Assessment Execution Engine (AXE.) It contains complete descriptions of the application programming interfaces and elements. The header files for using the unmanaged C++ version of the AXE APIs are installed with the "Windows Assessment Toolkit" feature of the [Windows Assessment and Deployment Kit (ADK)](6fe09525-f188-4668-be54-f222a8d1647b).

The AXE object model is a managed assembly used for programmatically creating, reading and writing assessment and job manifests. It is contained in the "Microsoft.Assessments.dll" in the [Windows Assessment and Deployment Kit (ADK)](6fe09525-f188-4668-be54-f222a8d1647b) under the "Windows Assessment Toolkit" installation. Currently, the only documentation for the interface is the public APIs discoverable through reflection.

## Run-time requirements

AXE and AXE assessments can be installed and run on Windows 7, Windows Server 2008 R2, Windows 8, or Windows Server 2012.

## In this section

-   [Unmanaged C++ Version of the AXE API](https://msdn.microsoft.com/library/windows/desktop/hh802981)
-   [AXE Schema Reference](https://msdn.microsoft.com/library/windows/desktop/hh449339)

 

 


