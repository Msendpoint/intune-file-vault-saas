# IntuneFileVault

> A self-service SaaS portal that lets IT admins securely upload, track, and audit custom data provider files to Intune devices via Microsoft Graph — without writing a single line of code.

## Overview

IntuneFileVault leverages the Microsoft Graph Beta customDataProvidedResourceUploadSession endpoint to provide a clean dashboard for uploading custom data files (referenceId-tracked) to managed Intune devices at scale. Admins can schedule uploads, monitor session status, and download audit logs per device or user group. The tool abstracts the complex multi-step Graph upload session flow into a point-and-click interface backed by automated PHP Graph API calls.

## Problem This Solves

The customDataProvidedResourceUploadSession API requires multi-step session creation, chunked file uploads, and referenceId tracking — a complex workflow that most IT admins cannot implement manually, causing them to skip the feature entirely or rely on expensive custom dev work

## Target Audience

IT admins and MSPs managing 200+ Intune-enrolled devices who need to push custom compliance data or reference files to endpoints without building internal tooling

## Tech Stack

PHP, Microsoft Graph, PowerShell, OAuth2, Intune

## Quick Start

```powershell
# Clone the repository
git clone https://github.com/intune-file-vault-saas.git
cd intune-file-vault-saas

# One-click install & run
.\Install.ps1

# Or run the script directly
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
.\scripts\{intune-file-vault-saas}.ps1
```

## Usage



## Monetization Strategy

SaaS Subscription: $29/month (up to 500 devices), $79/month (up to 5,000 devices), $149/month (unlimited / MSP white-label). One-time PowerShell source code bundle also sold at $149 for shops that prefer on-prem scripts.

| Metric | Value |
|--------|-------|
| Revenue Potential | HIGH |
| Estimated Effort  | 1-3months |

## About the Author