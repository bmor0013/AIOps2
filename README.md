# AIOps Log collector

This repo has been updated to work with `Python v3.8` and up.

### How To Run
pip3 install virtualenv

sudo apt install virtualenv

virtualenv env

source env/bin/activate

(env)   pip3 install -r requirements.txt

(env)   python3 app.py

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```# AIops
