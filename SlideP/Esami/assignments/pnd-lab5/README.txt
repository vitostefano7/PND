NOTICE: there is a issue for the connection when using virtualized machines (like the once in Katharà). To fix it, add this line at the end of EACH .startup file:
ethtool -K eth0 tx off