Example of a graderutils exercise, where the problem is to implement a simple prime number checker `primes.is_prime`.
An incorrect solution can be found in `primes.py`, which is compared against the reference solution `model.py`.

Run the tests to get test results in JSON (use develop mode to generate all errors and warnings):
```
python3 -m graderutils.main test_config.yaml --develop-mode > results.json
```
Convert the JSON results into HTML:
```
cat results.json | python3 -m feedbackformat.html --full-document > results.html
```
You can now view `results.html` in a browser.