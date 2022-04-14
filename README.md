## VR Challenge 3D painting - Simon Baeck

Uitgevoerde taken:
#### 1. The Canvas that allows you to change the shape on the pedestal follows the camera.
- Render mode aangepast naar "world space" bij de canvas_pedestal, stond eerst op "screen space".
#### 2. The medium brush size button turns invisible when pressed and makes the trail gigantic.
- Kleur aangepast van de medium_size naar de kleur die de rest ook heeft.
- De trail width aangepast in het "OnClick" event naar 0.025 om het minder groot te maken en tussenin de 2 anderen zit.
#### 3. The paint brush sound effect stays the same, regardless of how far it is from you.
- Verlagen van de min. afstand naar 0.1 en max. afstand naar 1 heeft het probleem opgelost.
#### 4. The toggled ray and palette canvas are tracking the opposite hands.
- Invoer referenties van de linker en rechterhand waren omgekeerd, na om te keren naar de juiste hand was het probleem opgelost. 
#### 5. The paint brush activation is backwards, starting when the trigger is released and stopping when it’s pressed.
- Bij de "OnActivate" en "OnDeactivate" acties waren de methodes omgekeerd gelinkt aan de "CreateTrail", na omkeren was het opgelost.
