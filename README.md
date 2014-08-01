rebrow - Python-Flask-based Browser for Redis Content
=====================================================

Built for the developer who needs to look into a Redis store.
Allows for inspection and deletion of keys. Also displays
some runtime and configuration information.

## Features

* Web based
* Runs in Python 2.7
* Lightweight requirements
* Search for keys using patterns
* Delete single keys
* Show server statistics

## Quick Start

Execute this:

    git clone https://github.com/marians/rebrow.git
    cd rebrow
    virtualenv venv
    source venv/bin/activate
    pip install -r requirements.txt
    python runserver.py

Then open [127.0.0.1:5001](http://127.0.0.1:5001).

## License

MIT licensed. See file LICENSE for details.

## Screenshots

![Start screen](https://farm4.staticflickr.com/3913/14615623267_c4a38b4fe1_c.jpg)

![Server status](https://farm3.staticflickr.com/2897/14615432280_b379e0f0af_c.jpg)

![Command stats](https://farm4.staticflickr.com/3902/14801787802_0c9b518f32_c.jpg)

![All Keys](https://farm4.staticflickr.com/3887/14615526428_ea251f2600_c.jpg)

![Keys matching a pattern](https://farm4.staticflickr.com/3887/14615482059_dda867f87f_c.jpg)

![Key details](https://farm6.staticflickr.com/5574/14779149896_f7194f0f7c_c.jpg)

