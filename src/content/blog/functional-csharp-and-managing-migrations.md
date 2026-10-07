---
title: 'Functional C# and Managing Migrations'
description: 'Notes on two talks: making C# more functional, and managing an application migration.'
pubDate: '2026-10-07'
---

## Making your C# more functional – Molly Painter

New C# features make this more practical than ever. The switch expression can replace most if statements and makes code easier to extend. What interested me most was the architecture: put the things you can't control (database, HTTP calls) in an outer shell, return a result object, and evaluate it in the business logic core. I'm not ready to give up OOP just yet, but I'll be using this pattern more.

## Managing an application migration – Kseniia Korostelova

This one focused less on the technical side and more on how the change was managed and governed. Three quotes stuck with me:

💬 "Write down what you are not doing." I've delivered features that drew complaints because someone assumed something was included. Nobody had said it wasn't.

💬 "Feature flags give you control. Retirement gives you value."

💬 "If nobody owns retirement, everyone owns maintenance." How many old features survive because one customer won't move and nobody wants to make the call? They become technical debt that confuses new developers about why we seem to do the same thing twice.
