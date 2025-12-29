---
title: 'GoDot笔记1:Node'
date: 2025-12-29
---

一个 Godot 游戏是一个由场景(scene)组成的树，而场景又是又一个由节点组成的数(node)

> a Godot game is a tree of scenes and that each scene is a tree of nodes

node 是构成游戏的基本模块，node 有很多种类，他们可以帮助你显示图片，播放音乐，作为相机。

所有的 node 都有下列特性：

- 名字
- 可编辑的属性
- 他们会在每一帧接收回调，进行更新(They receive callbacks to update every frame.)
- 你可以用新属性和函数来拓展他们
- 你可以让他们作为其他 node 的子节点
