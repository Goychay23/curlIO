  GNU nano 8.1                                                                                                     README.md                                                                                                      Modified  
CURLIO is an advanced http library. It comes with the genhttpv1library collection that offers advanced features. curlio has multiple functions. It takes its basic structure from libraries like curl.
#example usage                  

```python
import curlinkhref

url = 'https://example.com'
ch = curlinkhref.create_curlink_href(url)

# 2. HTTP metodunu ayarlayın (GET, POST, vb.)
curlinkhref.set_http_method(ch, 'GET')

# 3. HTTP isteğini gerçekleştirin
curlinkhref.perform_request(ch)

# 4. Kaynakları temizleyin
curlinkhref.cleanup_curlink_href(ch)

Although the code structure is like this, it has a modular structure and has been developed in a way that it can be easily integrated or developed 















