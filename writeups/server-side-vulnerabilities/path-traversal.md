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
