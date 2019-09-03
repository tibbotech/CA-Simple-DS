# Simple Device Server



This project implements the simplest "serial device server" possible. There is a single TCP connection. Once this connection is established, whatever is received through TCP is sent out via the serial port and vice versa.

The project comes in four different variations - each progressively more sophisticated.

- Without active opens, without buffer redirection
- Without active opens, with buffer redirection
- With active opens, without buffer redirection
- With active opens, with buffer redirection

