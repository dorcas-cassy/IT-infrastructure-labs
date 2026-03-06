# Intune Compliance Policy Concepts

## What is Microsoft Intune?

Microsoft Intune is a cloud-based endpoint management solution that allows organizations to manage devices, enforce security policies, and protect company data.

It works together with Microsoft Entra ID to control access to company resources.

## What is a Compliance Policy?

A compliance policy is a set of rules that devices must meet to be considered secure and compliant.

If a device does not meet these requirements, it can be marked as **non-compliant** and blocked from accessing company resources.

Examples include:

- Requiring BitLocker encryption
- Requiring a password
- Enforcing antivirus protection
- Ensuring Secure Boot is enabled

## Why Compliance Policies Matter

Compliance policies ensure that only secure and properly configured devices can access corporate data.

This helps organizations:

- Protect sensitive information
- Prevent unauthorized access
- Maintain security standards
- Enforce device health requirements

## What Happens When a Device is Non-Compliant?

When a device does not meet compliance requirements:

1. The device is marked **non-compliant**
2. Conditional Access policies can block access
3. Administrators can notify users
4. Access to company resources may be restricted

## Assignment of Compliance Policies

Policies are assigned to **Azure AD groups**.

In this lab, the policy was assigned to:

IT Department group

This simulates a real enterprise environment where policies are applied to specific teams.


## Key Security Settings Configured in this Lab

- BitLocker encryption required
- Secure Boot requirement
- TPM requirement
- Password complexity
- Microsoft Defender Antivirus enabled
