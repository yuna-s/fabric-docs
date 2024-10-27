---
title: Known issue - Dataverse shortcut creation and read fails when organization is moved
description: A known issue is posted where Dataverse shortcut creation and read fails when organization is moved.
author: mihart
ms.author: jessicamo
ms.topic: troubleshooting  
ms.date: 10/23/2024
ms.custom: known-issue-895
---

# Known issue - Dataverse shortcut creation and read fails when organization is moved

You can use a shortcut to see data from your Dataverse in a lakehouse. However, when the Dataverse organization is moved to a new storage location, the shortcut stops working.

**Status:** Open

**Product Experience:** OneLake

## Symptoms

Dataverse shortcut creation/read fails if the underlying Dataverse organization is moved.

## Solutions and workarounds

You can work around the issue by deleting and recreating the shortcuts.

## Next steps

- [About known issues](https://support.fabric.microsoft.com/known-issues)