GTInput
=======

**Important**

NGUI Unity Extension is required. This code only work with NGUI on your project.

Input Controller for NGUI Buttons that enables Unity like Input (Key mapping, GetButtonDown, GetButton....).

**How to**

1. Buy/Import NGUI
2. Add GTInputManager to your scene Camera or Character
3. Add GTButton to your NGUI Button (any widget that receive OnClick)
4. Get a reference to GTInputManager and use .GetButton or .GetButtonDown using Button GameObject Name. Example:

_GTInputManager.GetButtonDown("RightButton");
