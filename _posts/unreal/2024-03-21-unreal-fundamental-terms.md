---
layout: post
title: Unreal Fundamental Terms
description: Unreal first step, understand the basic elements.
date: 2024-03-21 20:20:00 +0900
tags: unreal
---

# Unreal Basic Glossary

### Levels ([Source](https://dev.epicgames.com/documentation/en-us/unreal-engine/levels-in-unreal-engine))

You can think of a level as a 3D environment into which you place a series of objects and geometry to define the world your players will experience ([link](https://dev.epicgames.com/documentation/en-us/unreal-engine/level-editor-in-unreal-engine#:~:text=You%20can%20think%20of%20a%20level%20as%20a%203D%20environment%20into%20which%20you%20place%20a%20series%20of%20objects%20and%20geometry%20to%20define%20the%20world%20your%20players%20will%20experience.)). Thus, it is part of the *game's world*.

To create a level, `.umap` file, mesh actors, lights, sound effects might be minimum requirements.

### Level Editor ([Source](v.epicgames.com/documentation/en-us/unreal-engine/level-editor-in-unreal-engine))

The scenes in the game experience are generally referred to as [**Levels**](#level-source).

### Viewport ([Source](https://dev.epicgames.com/documentation/en-us/unreal-engine/using-editor-viewports-in-unreal-engine?application_version=5.3))

Viewports are the windows. It indicates a world in Unreal we create for. It's in **[LevelEditor](#level-editor)**.

**Perspective** view is a 3D, and **orthographic** views are 2D, which displays one of the main axes.

**Game View** is a displaying mode, which would appear in the game playing. Let me understand as a simulation of the visualisation of the gaming.

### Component ([Source](https://dev.epicgames.com/documentation/en-us/unreal-engine/basic-components-in-unreal-engine))

Piece of functionality that can be added to an Actor. But they are not objects, so they don't exist as Actors exist themselves.

Unreal document explains the relations between components and actors as wheels inside the car and the entire cars ([Highlighted Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/basic-components-in-unreal-engine#:~:text=A%20Car%20class%20might%20use%20Components%20to%20represent%20the%20wheels%20of%20the%20car.)).

### Actor ([Source](https://dev.epicgames.com/documentation/en-us/unreal-engine/actors-and-geometry-in-unreal-engine))

Actor is a class of 3D object, which has position, rotation and scale data ([link](https://dev.epicgames.com/documentation/en-us/unreal-engine/level-editor-in-unreal-engine#:~:text=Actor%20is%20a%20programming%20class%20used%20within%20the%20Unreal%20Engine%20to%20define%20an%20object%20that%20has%203D%20position%2C%20rotation%2C%20and%20scale%20data.)). They are regarded as the objects, which would be created, destroyed through the gameplay code. They are moved, scaled to create environment or behave actively in game.

#### Pawn ([Source](https://dev.epicgames.com/documentation/en-us/unreal-engine/pawn-in-unreal-engine))

Pawn is a physical object which intereacts with the world by collision or other physical interactions. Pawn is a part of the **actors** ([link](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-actors-reference#:~:text=the%20physical%20representation%20of%20a%20player%20or%20AI%20entity%20within%20the%20world)). It is interacted by the players' control. In **Blueprints**, the best way to add movement to your Pawn-derived-class.

### Outliner ([Source](https://dev.epicgames.com/documentation/en-us/unreal-engine/outliner-in-unreal-engine))

[Hierarchical tree view of all Actors within the current Level](https://dev.epicgames.com/documentation/en-us/unreal-engine/outliner-in-unreal-engine#:~:text=Hierarchical%20tree%20view%20of%20all%20Actors%20within%20the%20current%20Level.).

Outliner can select and modify [Actors](#actor-source). Outliner can perform several actions toward Actors.

## Terminology ([Source](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-terminology))

### Blueprint

Bluerpint is a visual scripting system in gameplay scripting. It's a node-based interface.

### Object

This is the most basic class in Unreal Engine. Almost everything like actors, pawns and components are inherits from an **Object**.  In C++, `UObject` is the base class of all objects.

- [For the further knowledge](https://dev.epicgames.com/documentation/en-us/unreal-engine/programming-in-the-unreal-engine-architecture)
