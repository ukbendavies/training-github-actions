# 2022 Learning Objectives

!!! example

    === "Unordered List"

        ``` markdown title="List, unordered"
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

    === "Ordered List"

        ``` markdown title="List, ordered"
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```


## Organisation

- [ ] get organized, create this list and work through the goals this year

## Technologies

### Docker

- [ ] learn about container composition
- [ ] understand how volumes are used
- [ ] learn about docker-compose
- [ ] understand container management e.g. start, stop, daemon etc.

## Projects

### Pi-hole

- [x] create a personal pi-hole in a docker container filtering locally on my laptop.
- [x] create a docker-compose config to manage the appliance.
- [ ] create a private git repo for my home infrastructure
  - [ ] sync the latest pi-hole config
  
### Raspberry PI

#### k8s or docker server?

- [ ] research various options for lightweight docker hosting on raspberry pie

#### print server

- [ ] investigate print serving solutions using docker hosted print server
- [ ] implement print server

## Personal website

- [ ] Investigate Github Actions for CICD publishing yo github pages
- [ ] realize value from all the tutorials etc I'm doing. Figure out how to publish my various articles, training and projects, possibly using GH Actions?

## Documentation

### GSudo - sudo for Windows

[GSudo - GitHub](https://github.com/gerardog/gsudo)

`winget install gerardog.gsudo`

- add sudo alias

## PowerShell profile load performance

https://devblogs.microsoft.com/powershell/optimizing-your-profile/
https://gist.github.com/matthewjdegarmo/9116187b246aef1b8087caea6a8e4730

****

## Useful tools

|Name|Description|
|:-  |:-         |
|https://codepoints.net/ |search for unicode and show information about the characters|
|https://shapecatcher.com/index.html|draw to identify a character - really cool|

## Tools to investigate

|Name|URL|Desc|Useful|
|:-|:-|:-|:-:|
|Zlocation|[ZLocation](https://github.com/vors/ZLocation)|maintains directory location history and search| [ ] |
|HaveIBeenPawned|[have I been pawned](https://haveibeenpwned.com/API/v2#APIVersion)|search to see if you've been hacked| [ ] |

****


## Docker troubleshooting

|Issue|Description|Solution|
|:-|:-|:-|
|Networking error|docker: Error response from daemon: Ports are not available: listen tcp 0.0.0.0:8000: bind: An attempt was made to access a socket in a way forbidden by its access permissions.|netcfg -d => reset the network stack to defaults|
