## Compilation

Make sure you have Intel's PinTool installed on your computer (Download from [the Download Page](https://www.intel.com/content/www/us/en/developer/articles/tool/pin-a-binary-instrumentation-tool-downloads.html)), and the environment variable `PIN_ROOT` is pointed to the installation path.

Then, run `make`.

## Run Tests

`make test BINARY=/path/to/binary`

## Reference

For more information, please refer to the Chapter "Build Your Own Tool" and "Pin's Makefile Infrastructure" in [Intel Pin User Guild](https://software.intel.com/sites/landingpage/pintool/docs/98612/Pin/doc/html/index.html)
