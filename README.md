# SSH-SOCKS utility for macOS

This is simple utility to use SSH-SOCKS proxy for macOS.
The utility can easily controls the proxy on the command line.

## Quick install

    cd $HOME && git clone https://github.com/yhirokawa/ssh_socks_macos.git && echo 'export PATH=${HOME}/ssh_socks_macos:$PATH' >> ~/.bashrc

## Usage

### Enable SOCKS proxy

1. open terminal app.
2. execute: `connect-socks-proxy ${proxy_server}`

### Disable SOCKS proxy

1. execute: `disconnect-socks-proxy`
2. close terminal app.

### Set default proxy server

    echo ${default_proxy_server} > ${this_repository_install_path}/.default_proxy_server

## License

    MIT License
    
    Copyright (c) 2020 Yuta Hirokawa
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
