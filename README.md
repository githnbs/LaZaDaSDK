#LaZaDaSDK
测试lazadaSdk集成

#引入SDK
    comcomposer require githnbs/lazada-sdk=dev-master
#测试代码   
    $lazop = new LazopClient('url','APPKEY','APPSECRET');
    $request = new LazopRequest('API as example','TYPE');
    $request->addApiParam(params[string]);
    var_dump($lazop->execute($request, 'APPTOKEN'));

