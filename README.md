# OCR-hosted-on-heroku


Add apt buildpack to heroku

heroku buildpacks:add --index 1 https://github.com/heroku/heroku-buildpack-apt


Create a file named Aptfile in the same directory as your app and these lines to it (for english)

tesseract-ocr
tesseract-ocr-eng
