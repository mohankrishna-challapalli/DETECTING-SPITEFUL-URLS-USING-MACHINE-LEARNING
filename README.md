# DETECTING SPITEFUL URLS USING MACHINE LEARNING
URLs are the main culprit for any web attacks such that any malicious intention
user can hack the identity of the legal person by sending the malicious URL.
Malicious URLs are a cornerstone of Internet criminal activities. The dangers of
these sites have created a demand for safeguards that protect end-users from
visiting them.

We are proposing a learning based approach such as Blacklisting to classify
Web sites into 3 classes: Benign, Spam and Malware and this analyzes the
Uniform Resource Locator (URL) itself without accessing the content of Web
sites and it eliminates the runtime latency and the possibility of exposing users
to the browser based vulnerabilities.

By employing learning algorithms, our scheme achieves better performance on
generality.

## EXISTING SYSTEM
Traditionally, so many Data Mining algorithms such as NN have
been proposed by researchers for identification of malicious
URLs. But these algorithms doesn’t perform efficiently. Existing
techniques and approaches for malicious web pages detection is
not fully suitable for detection of malicious urls. Existing system
used non-machine learning approach such as Blacklisting.

Disadvantages:
• The error rate high in real time
• The accuracy was much less.

## PROPOSED SYSTEM
- We make use of certain features of a URL such as number of
slashes, keyword within path portion of URL, etc., to determine
whether a URL is a malicious URL or not. Lexical features are based
on the observation that the URLs of many illegal sites look different,
compared with legitimate sites.

- We first distinguish the two parts of a URL: the host name and the
path, from which we extract bag-of-words (strings delimited by ‘/’, ‘?’,
‘.’, ‘=’, ‘-’ and ‘’). After obtaining the required information about a
number of URLs, we just need to perform classification using
Random Forest algorithm.

## Requirements:
### A) Functional Requirements:

1. User is allowed to give any urls which is benign, spam and malware urls.
2. User is allowed to give url and it checks whether there is spelling mistake
and gives a output as benign, spam and malware urls.

### B) Non- Functional Requirements:
1. Performance
2. Reliability

### C) Software Requirements:
 Dataset
 Python 3.7
 Windows 7,8,10 (64-bit)

### D) Hardware Requirements:
 Processor : Intel CORE i3
 RAM : 4GB
