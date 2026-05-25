# Privacy Policy for EBIR Power BI GPT

**Last updated:** May 25, 2026

## 1. Controller

This integration is managed by **EBIR Iluminación S.L.** for internal or authorized business use.

This privacy policy describes how data is handled when using the EBIR Power BI GPT integration with Microsoft Power BI through the official Power BI REST API.

## 2. Purpose of the Integration

The purpose of this GPT is to allow authorized users to query Power BI content conversationally from ChatGPT.

The integration may be used to retrieve information such as:

- Power BI workspaces
- Reports
- Semantic models / datasets
- Metadata related to Power BI assets
- Analytical results returned by Power BI queries

The integration is intended for business analysis, reporting support, and internal decision-making.

## 3. Data Processed

The integration may process the following types of data:

- The corporate identity of the authenticated user through Microsoft Entra ID
- Power BI metadata, including workspace names, report names, dataset names, semantic model names, and related identifiers
- Results returned by Power BI REST API calls
- User prompts submitted in ChatGPT when requesting Power BI information
- Technical authentication data required to complete OAuth-based access

The integration does not intentionally collect or process personal data beyond what is required for authentication, authorization, and authorized Power BI access.

## 4. Authentication and Authorization

Access to Power BI is performed through **OAuth authentication with Microsoft Entra ID**.

The integration uses delegated permissions, meaning it acts on behalf of the authenticated user. It can only access Power BI content that the authenticated user is already authorized to access under Microsoft Power BI permissions.

The intended permissions are read-only:

- `Dataset.Read.All`
- `Report.Read.All`
- `Workspace.Read.All`

The integration is not intended to modify, delete, refresh, publish, or write content in Power BI.

## 5. Data Sharing

To provide the service, data may be transmitted between the following systems:

- ChatGPT / OpenAI, as the conversational interface
- Microsoft Entra ID, for OAuth authentication
- Microsoft Power BI, as the source of reports, datasets, semantic models, and analytical data

EBIR does not sell personal data or use data accessed through this integration for advertising purposes.

## 6. Data Storage

EBIR does not create an additional permanent database of Power BI responses through this GPT Action.

However, conversations and API interactions performed through ChatGPT may be processed and retained according to the applicable OpenAI terms, workspace settings, and data retention policies.

Microsoft Entra ID and Microsoft Power BI may also retain authentication, audit, and access logs according to Microsoft’s applicable policies and the organization’s tenant configuration.

## 7. Security

The integration uses OAuth-based authentication and delegated Microsoft Entra ID permissions.

Access is limited by:

- The authenticated user’s Microsoft identity
- The user’s existing Power BI permissions
- The permissions granted to the registered Microsoft Entra application
- The Power BI REST API endpoints explicitly configured in the GPT Action

The integration should be configured with the minimum permissions required and should avoid unnecessary read-write or administrative permissions.

## 8. User Responsibilities

Users must only request information they are authorized to access.

Users must not use the integration to extract, disclose, or share confidential, restricted, or personal data beyond their authorized business purpose.

Users should avoid submitting unnecessary personal, confidential, or sensitive information in prompts.

## 9. Third-Party Services

This integration depends on services provided by:

- OpenAI / ChatGPT
- Microsoft Entra ID
- Microsoft Power BI

Use of those services is subject to their respective terms, privacy policies, security controls, and data processing conditions.

## 10. Changes to This Policy

EBIR may update this policy to reflect technical, legal, operational, or security changes related to the integration.

Updates will be published on this page.

## 11. Contact

For questions about this integration or this privacy policy, users should contact EBIR Iluminación S.L. through the usual corporate communication channels.
