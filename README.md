# RouteMap

Fork of ImOsmDemo. Shows transport stations on an OpenStreetMap map and builds routes between them using the Yandex Schedule API.

Requests to the Yandex API and route searches run on a separate thread, so the window doesn't freeze while waiting for the network.

![demo](doc/show2.gif)
![map](doc/show1.png)

## Ubuntu dependencies

ImGui with the GLFW backend needs:

    sudo apt install libx11-dev libxrandr-dev libxinerama-dev libxcursor-dev libxi-dev freeglut3-dev

ImOsmWidget needs libcurl:

    sudo apt install libcurl4-gnutls-dev
