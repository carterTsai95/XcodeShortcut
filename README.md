# Xcode Shortcut

  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#toggle-minimap">Toggle Minimap</a>
    </li>
    <li><a href="#editor">Editor</a></li>
      <ul>
        <li><a href="#focus-editor">Focus Editor</a></li>
      </ul>
    <li><a href="#editors-tab">Editor's tab</a></li>
    <li><a href="#code-editing">Code Editing</a></li>
    <li><a href="#navigation">Navigation</a></li>
  </ol>
</details>

# Mac keyboard symbols

| ⌘ = Command | ⌥ = Option/Alt     | ⇧ = Shift |
|-------------|--------------------|-----------|
| ⌃ = Control | ←→ ↑↓ = Arrow keys | ↩ = Enter |

## Toggle Minimap

- (⌃ Control) + (⇧ Shift) + (⌘ Command) + M
- Alternative: Editor > Minimap


<p align="center">
	<img width="600" src="Media/MiniMap.gif" alt="Mini Map" />
</p>


## Editor

###Focus Editor

- (⌘ Command) + (⌃ Control) + (⇧ Shift) + ⏎ Return
- Alertnative: View > Editor > Focus/Hide Focus

Juggling multiple editors is a common challenge. While sometime I will have multiple editors open for reviewing, when I need to focus on one specific editor but I also don't want to close others. This shortcut becomes really handy. Ensuring that the editor you need is always at the forefront.

<p align="center">
	<img width="600" src="Media/FocusEditor.gif" alt="Focus Editor" />
</p>

------

###Find the function caller

- Prerequisite: The functon need to be highlighted.
- (⌃ Control) + 1 -> Move to caller tab

I often using this shortcut while knee-deep in a gaint codebase for some complicate function or busniness logic. Instead of manually combing through the project to discover its various callers, with a this shortcut, I can seamlessly navigate to the caller tab. And gain a deeper understanding of the project's architecture.

<p align="center">
	<img width="600" src="Media/FindTheFunctionCaller.gif" alt="FindTheFunctionCaller" />
</p>

------

###Show document items

- (⌃ Control) + 6

This shortcut comes handy once we need to check all the function, variable, class or extenion etc... in the file. This would open up the tab that help visualize the those in the current file.

<p align="center">
	<img width="600" src="Media/ShowDocumentItems.gif" alt="Show Document Items" />
</p>

------

## Editor's Tab

###Switch Tab

- (⌘ Command) + (⇧ Shift) + [ (Switch from right to left)
- (⌘ Command) + (⇧ Shift) + ] (Switch from left to right)

If there are multiple tabs in one editor and we want to navigate through the neighbor's tab quickly. This shortcut is the one you are looking for.

<p align="center">
	<img width="600" src="Media/SwitchTab.gif" alt="SwitchTab.gif" />
</p>

------

###Open New Editor on the right

- (⌘ Command) + (⌃ Control) + T

Whenever we need to add the extra editor, using this shortcut it help us directly open current seletected file as the new editor and append to the right side.

<p align="center">
	<img width="600" src="Media/OpenEditorOnRight.gif" alt="Open New Editor on the right" />
</p>

------

###Close current editor

- (⌘ Command) + (⌃ Control) + (⇧ Shift) + W

This shortcut will close the focused Editor.

<p align="center">
	<img width="600" src="Media/CloseCurrentEditor.gif" alt="Close the current Editor" />
</p>

## Code Editing

###Code Completion

- (⌃ Control) + Space

One of my favorite shortcut while exploring the new field of the codebase. "Show Quick Help" opens a pop-up window displaying quick documentation and information about that specific API or code symbol. This is helpful for exploring the details of APIs, functions, and classes without having to navigate away from current tab.

<p align="center">
	<img width="600" src="Media/CodeCompletion.gif" alt="Code Completion" />
</p>

------

###Re-indent

- (⌃ Control) + I

This helps to re-indent the selected area's indent.

<p align="center">
	<img width="600" src="Media/ReIndent.gif" alt="ReIndent" />
</p>

------

###Comment the code

- (⌘ Command) + /

This action adds or removes comment markers, making it easy to annotate your code for clarity or temporarily disable sections during development.

<p align="center">
	<img width="600" src="Media/CommentCode.gif" alt="Comment the code" />
</p>

------

## Navigation

###Jump to Definition

- (⌘ Command) + (⌃ Control) + J or (⌘ Command)
- or  (⌃ Control) + Click

With this shortcut it can navigate to the definition of a symbol, function or a class. It is often useful when we need to check where is this symbol, function or class is declared.

<p align="center">
	<img width="600" src="Media/JumpToDefinition.gif" alt="Jump to definition" />
</p>

------

###Find Call Hierarchy

- (⌘ Command) + (⌃ Control) + (⇧ Shift) + H

If the function/property that we know is deep nested inside other's propery. Find call Hierarchy help us to visualize the hierarchy of the call.

<p align="center">
	<img width="600" src="Media/FindCallHierarchy.gif" alt="FindCallHierarchy" />
</p>

------

###Find Select Symbol in Project

- (⌘ Command) + (⌃ Control) + (⇧ Shift) + F

Normally we will using the (⌘ Command) + F to find the match String in the project. But this won't narrow down to the specific property that we are actually looking for since there might have the chance we have same property called "name".

With this shortcut it will only list the highlighted propery as the result which is quite helpful if we are searching for some properties/function might have same name.

<p align="center">
	<img width="600" src="Media/FindSelectedSymbol.gif" alt="Find Selected Symbol" />
</p>

------

###Open Quickly

- (⌘ Command) + (⇧ Shift) + O

This oftenly use when developer have the file that already in mind. By using this shortcut, it prevent developer navigate through the whole heirachy in the project folder.

Sometime it also use while code reviewing, other developer might have more knowledge on the feature that is worked on. This shortcut could help developer sommon the file open on the editor with the ease.

<p align="center">
	<img width="600" src="Media/OpenQuickly.gif" alt="Open Quickly" />
</p>

------

###Highlight File in Project Navigator

- (⌘ Command) + (⇧ Shift) + J

When the project has the thousand files, sometimes is hard to find the specific file in the folder. This shortcut is come to rescue for directly highlight the file and navigate deep down to the folder.

<p align="center">
	<img width="600" src="Media/HighlightFile.gif" alt="HighlightFile" />
</p>