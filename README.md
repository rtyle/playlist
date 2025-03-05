# playlist

Embed m3u8 playlists into music libraries, specified by their roots.

Each music library’s root directory is traversed looking for music files.
All music files in a directory (and below)
are aggregated/embedded into a playlist in the directory’s parent.
The playlist is named for the path from the root to this parent directory,
with slases replaced with dots and an .m3u8 file extension.

## Deployment

Git this repository as appropriate. For examples,

    git clone https://github.com/rtyle/playlist.git
    git clone git@github.com:rtyle/playlist.git

## Usage

(cd parent; playlist root...)
