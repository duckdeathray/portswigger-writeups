Path Traversal / Directory Traversal
  -> read arbitrary files on server such:
      - application code and data
      - credentials for back end
      - sensitive OS files
  -> write arbitrary files on server
  
Method:
  -> instead of acccessing and following the path it's supposed to, attacker can request another URL to retrieve sensitive files

Example:
  https://insecure-website.com/loadImage?filename=../../../etc/passwd

**Lab: path traversal, simple case**
1. Load website and click on any GET request loading an image
2. Replace the filename with ../../../etc/passwd
