# url_shortener_expander
URL Shortener and expander URL CLI Tool 
## CLI Usage
1. Using Bash
* To shorten an URL
```bash
cd ~/
git clone https://github.com/kinghub007/url_shortener_expander.git
cd url_shortener_expander
bash short -s https://example.com
```
* To expand an URL
```bash
bash short -e  https://tinyurl.com/peakb
``` 
2. Using Python
The package `python3-pyshortener` needs to be installed first. Choose between 1 or 2 to perform the required operation.
```bash
pip install pyshorteners
python3 short_python
```
