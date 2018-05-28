# UE4-VisualAssist-Snippets
A personal record of handy visual assist snippets for Unreal Engine 4.

uebind
--------

Quickly bind your axis/action functions.
```
$PlayerInputComponent$->Bind$Axis$("$Turn$", $Event=,$ this, &A$FILE_BASE$::$MyFunc$);$end$
```

uelog
-------
Quickly log a message to the console.
```
UE_LOG($LogTemp$, $Warning$, TEXT("$Message$"))$end$
```
