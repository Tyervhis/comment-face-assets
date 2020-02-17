# [/r/anime](https://www.reddit.com/r/anime) Comment Face Assets

The repository of media and data of [/r/anime](https://www.reddit.com/r/anime) Comment Faces.

## Directory Structure
* `preview`
  Preview of Comment Faces in the dimension used by the [/r/anime](https://www.reddit.com/r/anime) stylesheet.
  * `active`
    Currently active Comment Faces.
  * `discontinued`
    Discontinued Comment Faces.

## List of Comment Faces

The data about the Comment Faces are stored in `comment_face_list.csv` with following fields:
* `name` - Name of the Comment Face (used in the link).
* `is_animated` - Whether the Comment Face is animated.
* `source_width` - The initial width of the source image(s).
* `source_height` - The initial height of the source image(s).
* `resized_width` - The width of the image(s) after resizing.
* `resized_height` - The height of the image(s) after resizing.
* `crop_top` - The number of pixels cropped from the top.
* `crop_bottom` - The number of pixels cropped from the bottom.
* `crop_left` - The number of pixels cropped from the left.
* `crop_right` - The number of pixels cropped from the right.
* `output_width` - The width of the image(s) after cropping.
* `output_height` - The height of the image(s) after cropping.
* `frame_count` - The number of frames (animated only).
* `duration_s` - The duration in seconds (animated only).
* `is_loop` - Whether the animation is looped (animated only).
* `released_on` - The date when the Comment Face was released.
* `discontinued_on` - The date when the Comment Face was discontinued.
* `notes` - Notes related to the Comment Face processing.
