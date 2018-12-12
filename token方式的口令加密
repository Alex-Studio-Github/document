# 从口令加密到token保护

1. token方式对口令登陆的增强.
   - server产生随机数token给client,
   - client用token给password做HMAC，
   - 服务器保存此HMAC，看不到password,token允许被泄露
2. 身份加密.
   - 基于身份的加密中，任何可以唯一标识用户身份信息的字符串都可以作为公钥，例如email地址、电话号码、姓名、工号等等。例如，CT Enc(M, liuzhen@sjtu.edu.cn) 直接用email地址加密数据M产生密文。
   - 由于“身份即公钥”，所以，不需要考虑身份与公钥绑定的问题，也就不需要PKI.比如，sm9
