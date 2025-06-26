# Enterprise Auth PoC

This Proof of Concept demonstrates a secure enterprise-ready authentication flow using Microsoft Entra ID (Azure AD), React (SPA), and .NET (BFF).

## Goals

- ✅ Integrate MSAL with Authorization Code Flow + PKCE
- ✅ Validate Entra ID tokens in .NET BFF
- ✅ Enforce access based on Entra ID roles or groups
- ✅ Optional: Extend with Identity Server for role/permission management

## Structure

| Folder            | Description                                  |
|-------------------|----------------------------------------------|
| `spa-react/`      | React SPA using MSAL for authentication      |
| `bff-api/`        | .NET Web API validating Entra ID access token|
| `identity-server/`| Optional IdentityServer for advanced scenarios|
| `docs/`           | Screenshots and setup guides (for Confluence)|

## Requirements

- Node.js (>=18)
- .NET 8 SDK
- Optional: Azure subscription with Entra ID (or Entra ID Developer tenant)

## Status

| Step                                      | Status  |
|-------------------------------------------|---------|
| Project Scaffold                          | ✅ Done |
| MSAL Integration (SPA)                    | ⏳ Pending |
| Token Validation in .NET BFF              | ⏳ Pending |
| Role-based access (Entra ID)              | ⏳ Pending |
| Documentation for Confluence              | ⏳ In Progress |
