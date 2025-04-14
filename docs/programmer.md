## 1. Style Guide

### 1.1 Unreal Engine

Follow the Allar ue5 style guide: [https://github.com/Allar/ue5-style-guide](https://github.com/Allar/ue5-style-guide)

### 1.2 Code Style

Readibility first. Camel case, can use snake case to divide if name is too long.

```
public:
    DialogueSystem
    GameManager

private:
    _dialogueSystem
    _gameManager
```

If you use snake case, the suffix is for giving context, stating its type.

```
SpeechBubble_UserInterface
OnCommandExecuted_MulticastDelegate
```

For private variables, first letter lower case and add _ in front of variable name. _ can avoid name conflicts with engine.

```
_colliderBox
_animator

animator => might cause warning due to name conflict with engine, variable hiding.
```

## 2. Version Control

### 2.1 Git

### 2.2 Collaboration Standards

#### 2.2.1 Branching strategies

#### 2.2.2 Commit conventions

#### 2.2.3 Merge Reviews

## 3. Game Systems

### 3.1 Level Generation

#### 3.1.1 Lane Visualizer

#### 3.1.2 Distance-based obstacle spawn

#### Bug records

##### Obscales overlap

Obstacles overlap continuously after a certain distance. It happens after

### 3.3 Online Services

#### 3.3.1 Player Accounts

#### 3.3.2 Player Saves

### 3.4 Multiplayer
