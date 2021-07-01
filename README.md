# go-cover-vim

This is a plugin which highlights go buffers in vim with coverage information from a coverage profile.
All the code was copied from vim-go, I didn't want all the rest of vim-go so I just copied what I needed.

I've been using it like this `call go#coverage#overlay('coverage.out')` you
need to call it for each buffer annoyingly.
