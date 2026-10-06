# minigame 2
On Step 2, line 27 on the Spells Script, there was a slight error with the If statement. It was missing the parentheses that surronds the "_timeLeft <= 0.0f". 

_spriteRenderer.color = new Color(r, 0.2f, 0.2f)
this line of code is setting the value of _spriteRenderer.color = new Color (r, 0.2f, 02.f). The _spriteRenderer.color refers to the color of the sprite.
the period seperates the component and the subcomponent. the .color is the subcomponent of _spriteRenderer that dictates the color of the sprite. Basically, the period tells the computer that the value being changed is the color of _spriteRenderer. Not the shape, not the size.
the word new is basically creating a new color. new means what it does here; it creates a fresh, new instance of a color here. the numbers in parentheses relate to values of 0.0-1.0 RGB. 

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
