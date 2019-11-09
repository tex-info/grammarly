[![Build Status](https://travis-ci.com/jcs090218/grammarly.svg?branch=master)](https://travis-ci.com/jcs090218/grammarly)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)


# grammarly
> Grammarly API interface.


## Examples

Below is an simple example that how you can use this library for calling 
Grammarly API interface.

```el
(require 'grammarly)

;; Set callback for receiving data.
(setq grammarly-on-message-function 
      (lambda (data)
        (message "[DATA] %s" data)))

;; Send check text request.
(grammarly-check-text "Hello World")
```


## References

* [grammarly-api](https://github.com/dexterleng/grammarly-api)
* [reverse-engineered-grammarly-api](https://github.com/c0nn3r/reverse-engineered-grammarly-api)


## Todo List

- [ ] Support multiple requests at the same time.


## Contribution

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
