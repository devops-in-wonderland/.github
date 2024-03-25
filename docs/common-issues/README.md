# Common Issues

## [Unable to Share Screen in Discord on Ubuntu](https://github.com/devops-in-wonderland/share-screen-discord-ubuntu/blob/main/UnableShareScreen.md)

1. Open the terminal and enter the following command:

```bash
echo $XDG_SESSION_TYPE
```

2. If the output is "wayland", uncomment or add ```WaylandEnable=false``` config in ```/etc/gdm3/custom.conf``` file.
3. Finally, restart your machine.

ISSUE RESOLVED :partying_face:
