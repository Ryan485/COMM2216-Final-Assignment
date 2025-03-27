Troubleshooting
==
## Forking

| Symptom | Possible Cause | Solution |
|---------|----------------|----------|
|  | | |

## Cloning

| Symptom | Possible Cause | Solution |
|---------|----------------|----------|
| Error 401/403 | `git` is not updated | [Update `git`](https://git-scm.com/downloads)| 
| | the `origin` points to something not recognised | [Change the `origin` URL](https://git-scm.com/downloads) | 
| `Error: ... not found` | The server information is not updated | **run** `git update-server-info` in the terminal|
| | The target repository is private, and you are not logged in | [log in to `git`](https://stackoverflow.com/questions/18935539/authenticate-with-github-using-a-token) |
