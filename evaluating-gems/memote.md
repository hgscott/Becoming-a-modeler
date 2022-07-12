# MEMOTE

## Notes to Self

To make a repo it tries to use your username and password to authenticate a user:

Line 594 in runner.py (setup\_gh\_repo function):

`requests.get("https://api.github.com/user", auth=credentials, headers=headers)`

Made an access token: ghp\_NsqxbQ954upoE0d62Z468AqtXG9ceL0qwR3r

