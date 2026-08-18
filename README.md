# DecodeLabs — Azure Cloud-Based Static Website

A Cloud Engineer portfolio website designed, developed, and deployed as a static website using Microsoft Azure Blob Storage.

## 🌐 Live Website

**Azure Static Website:**

https://rgdecodelabs.z58.web.core.windows.net/

## 📌 Project Overview

This project demonstrates the deployment of a static portfolio website on Microsoft Azure using an Azure Storage Account and Azure Blob Storage static website hosting.

The website was developed locally using HTML and CSS, version-controlled with Git, stored on GitHub, and deployed to Azure Static Website hosting.

## 🎯 Project Objectives

- Build a professional Cloud Engineer portfolio website.
- Deploy a static website using Microsoft Azure.
- Use Azure Blob Storage for website hosting.
- Configure a custom error page.
- Manage source code using Git and GitHub.
- Test the deployed website and navigation.
- Document the complete cloud deployment workflow.

## 🏗️ Architecture

```text
                    Internet
                       │
                       ▼
              ┌─────────────────┐
              │   Web Browser   │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ Azure Static    │
              │ Website         │
              │ Endpoint        │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ Azure Storage   │
              │ Account         │
              │ rgdecodelabs    │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ $web Container  │
              ├─────────────────┤
              │ index.html      │
              │ style.css       │
              │ 404.html        │
              └─────────────────┘