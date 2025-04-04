---
layout: post
---

# Audio

The `audio` tag displays an HTML audio player with a specified file.

## Properties

**[caption](#basic-example)** (_string_): Defines the text to use for a caption that is displayed below the video player.

**[nocaption](#basic-examples)** (_boolean_):  This property inhibits the display of the caption at the bottom of the player.

**[src](#basic-example)** (_url_):  A URL to the audio file to play.

### Positioning properties

**[left](#positioning-examples)** (_boolean_):  Align the component with the left side of the window.  The components width is 50% of the window and any section text following the component tag will wrap around the component.

**[right](#positioning-examples)** (_boolean_):  Align the component with the right side of the window.  The components width is 50% of the window and any section text following the component tag will wrap around the component.

**[center](#positioning-examples)** (_boolean_):  The component is centered in the window.

**[large](#positioning-examples)** (_boolean_):  The component is sized to 75% of the window.

**[medium](#positioning-examples)** (_boolean_):  The component is sized to 50% of the window.

**[small](#positioning-examples)** (_boolean_):  The component is sized to 33% of the window.


## Examples

### Basic examples

#### Simple Audio player

##### &nbsp;
{: .tabs}

###### Markdown

```markup
`audio src=https://upload.wikimedia.org/wikipedia/commons/6/65/Wikipedia_-_Earth_(spoken_by_AI_voice).mp3`
```

###### HTML

```html
<iframe
  src="https://ifc.juncture-digital.org/audio?src=https://upload.wikimedia.org/wikipedia/commons/6/65/Wikipedia_-_Earth_(spoken_by_AI_voice).mp3"
  allowfullscreen
></iframe>
```

###### Rendered

`audio src=https://upload.wikimedia.org/wikipedia/commons/6/65/Wikipedia_-_Earth_(spoken_by_AI_voice).mp3`


#### Using Wikimedia Commons "wc:" Prefix

##### &nbsp;
{: .tabs}

###### Markdown

```markup
`audio src=wc:Wikipedia_-_Earth_(spoken_by_AI_voice).mp3`
```

###### HTML

```html
<iframe
  src="https://ifc.juncture-digital.org/audio?src=wc:Wikipedia_-_Earth_(spoken_by_AI_voice).mp3"
  allowfullscreen
></iframe>
```

###### Rendered

`audio src=wc:Wikipedia_-_Earth_(spoken_by_AI_voice).mp3`


#### Using GitHub Hosted Audio File

##### &nbsp;
{: .tabs}

###### Markdown

```markup
`audio src=gh:schh-commons/podcasts/main/SunSations_April_2025.mp3`
```

###### HTML

```html
<iframe
  src="https://ifc.juncture-digital.org/audio?src=gh:schh-commons/podcasts/main/SunSations_April_2025.mp3"
  allowfullscreen
></iframe>
```

###### Rendered

`audio src=gh:schh-commons/podcasts/main/SunSations_April_2025.mp3`