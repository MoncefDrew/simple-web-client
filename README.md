# simple-web-client

a simple http client made using c ,it receives the url and returns an http response.

You can compile and run web_get.c on Linux and macOS with the following commands:

<pre><code>gcc web_get.c -o web_get
./web_get http://example.com/
</code></pre>

On Windows, the command to compile and run using MinGW is as follows:

<pre><code>gcc web_get.c -o web_get.exe -lws2_32
web_get.exe http://example.com/
</code></pre>
