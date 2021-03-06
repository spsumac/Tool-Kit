MAC Guide - Networking
========

Inside of the MAC Guide - Networking folder are 8 projects (4 Network Clients, and 1 Network Server).

The Server is a pure [Java](http://www.java.com/en/download/faq/develop.xml) application, that starts a [TCP](http://www.webopedia.com/TERM/T/TCP.html) Server awaiting for connections from its clients. The clients are [Android](http://www.android.com/index.html) and [iOS](https://www.apple.com/ios/) projects, that can send a message to the Wifi Server that is altered and returned to the [Client](http://en.wikipedia.org/wiki/Client_(computing)).

# Servers
[Wifi Network Server](https://github.com/the-mac/Tool-Kit/tree/master/MAC%20Guide%20-%20Networking/Wifi%20Server) - [MAC Guide](https://github.com/the-mac/Tool-Kit/wiki/Java-Server-(Eclipse)---HowTo)
========
The Server is a pure [Java](http://www.java.com/en/download/faq/develop.xml) application titled [Server.java](https://github.com/the-mac/Tool-Kit/blob/master/MAC%20Guide%20-%20Networking/Wifi%20Server/src/Server.java), that starts a [TCP](http://www.webopedia.com/TERM/T/TCP.html) connection awaiting clients. The Server must be connected to a Wifi Network to allow the clients to connect to it locally (on the same Wifi Network).

[PHP JSON API](https://github.com/the-mac/Tool-Kit/blob/master/MAC%20Guide%20-%20Networking/PHP%20JSON%20API)
========
The JSON API is a pure [PHP](http://php.net/) application titled [server.php](https://github.com/the-mac/Tool-Kit/blob/master/MAC%20Guide%20-%20Networking/PHP%20JSON%20API/server.php), that awaits clients. The script must be placed on a Server with php installed to allow the clients to connect to it.

# Clients
Android Client
========

The [Android](http://www.android.com/index.html) client project is built in [Android Studio](http://developer.android.com/tools/studio/index.html). The project has 1 Major file titled [NetworkClient.java](https://github.com/the-mac/Tool-Kit/blob/master/MAC%20Guide%20-%20Networking/AndroidClient/app/src/main/java/us/mac/the/networking/NetworkClient.java), and 2 lesser/supporting files for strings and visual layouts.

[Android Eclipse Client](https://github.com/the-mac/Tool-Kit/tree/master/MAC%20Guide%20-%20Networking/AndroidEclipseClient) - [MAC Guide](https://github.com/the-mac/Tool-Kit/wiki/Android-Network-(Eclipse)--HowTo)
========

The [Android](http://www.android.com/index.html) client project is built in [Eclipse](https://eclipse.org/). The project has 1 Major file titled [NetworkClient.java](https://github.com/the-mac/Tool-Kit/blob/master/MAC%20Guide%20-%20Networking/AndroidEclipseClient/src/us/mac/the/networking/NetworkClient.java), and 2 lesser/supporting files for strings and visual layouts.

[iOS Client](https://github.com/the-mac/Tool-Kit/tree/master/MAC%20Guide%20-%20Networking/iOS%20Client) - [MAC Guide](https://github.com/the-mac/Tool-Kit/wiki/iOS-Network-(Xcode)-HowTo)
========

The [iOS](https://www.apple.com/ios/) client project is built in [Xcode](https://developer.apple.com/xcode/). The project has 1 Major file titled [NetworkClient.m](https://github.com/the-mac/Tool-Kit/blob/master/MAC%20Guide%20-%20Networking/iOS%20Client/iOS%20Client/NetworkClient.m), and 4 lesser/supporting files for network connection and visual layouts.

[iOS Swift Client](https://github.com/the-mac/Tool-Kit/tree/master/MAC%20Guide%20-%20Networking/iOS%20Swift%20Client) - [MAC Guide](https://github.com/the-mac/Tool-Kit/wiki/iOS-Swift-Network-(Xcode)-HowTo)
========

The [iOS](https://www.apple.com/ios/) client project is built in [Xcode](https://developer.apple.com/xcode/). The project has 1 Major file titled [NetworkClient.swift](https://github.com/the-mac/Tool-Kit/blob/master/MAC%20Guide%20-%20Networking/iOS%20Swift%20Client/iOS%20Swift%20Client/NetworkClient.swift), and 3 lesser/supporting files for network connection and visual layouts.
