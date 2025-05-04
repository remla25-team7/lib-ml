# lib-ml

Shared preprocessing logic for restaurant sentiment analysis.

## Usage

```python
from lib_ml.preprocessing import clean_review, tokenize_review

txt = "I didn't like this place!"
print(clean_review(txt))
# → "i didnt like this place"

print(tokenize_review(txt))
# → ["didnt","like","place"]