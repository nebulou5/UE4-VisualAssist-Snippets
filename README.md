# UE4-VisualAssist-Snippets
A record of handy visual assist snippets for Unreal Engine 4.

uebeginplay
--------
```
void A$FILE_BASE$::BeginPlay() {
  $end$
}
```

uebind
--------
```
$PlayerInputComponent$->Bind$Axis$("$Turn$", $Event=IE_Pressed,$ this, &A$FILE_BASE$::$MyFunc$);$end$
```

uecheck
--------
```
check($Pointer$ != nullptr);$end$
```

ueco
--------
```
A$FILE_BASE$::A$FILE_BASE$() {
  $end$
}
```

uecdso
--------
```
CreateDefaultSubobject<$USceneComponent$>(TEXT("$Root$"));
$end$
```

uelog
-------
```
UE_LOG($LogTemp$, $Warning$, TEXT("$Message$"))$end$
```

ueoverlap
--------
```
void A$FILE_BASE$::HandleOverlap(
  UPrimitiveComponent* OverlappedComponent,
  AActor* OtherActor,
  UPrimitiveComponent* OtherComp,
  int32 OtherBodyIndex,
  bool bFromSweep,
  const FHitResult & SweepResult
) {
  //Don't forget to bind
  //OverlapComp->OnComponentBeginOverlap.AddDynamic(this, &MyClassName::HandleOverlap);
  $end$
}
```

ueprintscreen
--------
```
if (GEngine) {
		GEngine->AddOnScreenDebugMessage(
		-1, 
		15.0f, 
		FColor::Yellow, 
		FString::Printf(TEXT("$say$: %$f$"), $Output$)
	);
}
$end$
```

uetick
--------
```
void A$FILE_BASE$::Tick(float DeltaTime) {
  Super::Tick(DeltaTime);
  $end$
}
```

