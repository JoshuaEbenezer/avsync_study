# Data genreation for AV Sync study

Offsets are created using the script `create_offset.py`. ffmpeg is called from inside the python script with specified offsets.

Offsets are applied on the entire YouTube video so that there is no period of silence in the final cut version.

Videos are then cut from the offset version using the `cut_videos.py` script.


