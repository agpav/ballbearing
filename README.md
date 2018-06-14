# ballbearing
New framework with following three layers.

## Interface Layer
External interaction of system,
User, DataBase, File System, External APIs etc
Stateless

## Model Layer
POJOs used to get/set data between interface layer and logic layer.
Stateful

## Logic Layer
Core logic of the system.
Stateless

## Context
Framework context to bind above all three layer and maintain the state.