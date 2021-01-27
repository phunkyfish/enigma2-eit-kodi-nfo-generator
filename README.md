# Description
Script to convert from enigma2 eit files to nfo files used by kodi

Ported to Python 3 from the Python 2 version sourced from: https://gist.github.com/marcohald/5a58698c71d36ae62a2ac897917eecac which was originally based on https://github.com/betonme/e2openplugin-EnhancedMovieCenter/blob/master/src/EitSupport.py.

# Using the script

`python3 enigma2-eit-kodi-nfo-generator.py <dir-name1> <dir-name2> ...`

The script will covert each `*.eit` file it finds in the specified directories.
# Dependencies
`pip3 install chardet`