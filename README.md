# COMP-4450-Assignment-3

## Endpoints

**http://127.0.0.1:8000/health**: GET endpoint confirming whether the API is running or not.
**http://127.0.0.1:8000/predict**: POST endpoint that takes an input movie review and returns the sentiment of the review (positive or negative).
**http://127.0.0.1:8000/predict_proba**: POST endpoint that takes an input movie review and returns the sentiment and the confidence score of the sentiment. i.e "positive", 0.95.
**http://127.0.0.1:8000/example**: GET endpoint that returns a random review from the original training dataset.

## Build & Run

1. Use `git clone https://github.com/jlarson-dev/COMP-4450-Assignment-3.git`
2. Run `make build`
3. Run `make run`
4. Use Postman to test the different endpoints.

## Documentation

http://127.0.0.1:8000/docs