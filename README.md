# X-Ladon, X-Gorgon, X-Argus video without watermark bot, account create, gorgon algorithm

## ICQ - @apitok - https://icq.im/apitok
## Skype - live:.cid.8e129461a4e880f7
## Telegram @tiktokpeppa

# TikTok-Douyin-Api
Security Our analysis of security issues in TikTok and Douyin resulted in the following high-level findings:  All of TikTok and most of Douyin’s network traffic were adequately protected using HTTPS. For some data, an additional layer of encryption, which we dubbed “ttEncrypt,” was employed. We engineered a way to intercept the clear-text data before they were encrypted with ttEncrypt. We examined the data and found no clear reason why these data had to be encrypted again on top of the existing transport encryption provided by HTTPS, as these ttEncrypt-ed data were not confidential. Most of TikTok and Douyin’s API requests are protected with a custom signature in the HTTP header named “X-Gorgon.” The signature is generated using a native library module, which made it difficult for us to understand its inner workings. We think the purpose of this signature is to prevent third-party programs from imitating and sending TikTok/Douyin API requests. We found that there are people selling and buying third-party implementations of ttEncrypt and X-Gorgon algorithms. These third-party implementations might be produced to serve the need of bots (programs disguised as real users). Douyin loads some of its code components via the Internet. It can also update itself without any user interaction. Such code loading was adequately protected using HTTPS, making it difficult for attackers to inject malicious code in the loading process. However, this feature is a security issue because it bypasses the operating system’s and user’s control of what code could run on the device. TikTok does not include this feature.
