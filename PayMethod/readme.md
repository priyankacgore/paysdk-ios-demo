# Pay Method

```
paySDK.paymentDetails = PayData(channelType: PayChannel.DIRECT,
                                envType: EnvType.SANDBOX,
                                amount :“1”,
                                payGate: PayGate.PAYDOLLAR,
                                currCode: currencyCode.HKD,
                                payType: payType.NORMAL_PAYMENT,
                                orderRef: "2018102409220001”,
                                payMethod: "VISA",
                                lang: Language.ENGLISH,
                                merchantId: "88146271",
                                remark: "",
                                payRef: "",
                                extraData :[])
                                
paySDK.query(action: "PAYMENT_METHOD")

//NOTE : For allowed Pay Method Response will come in below format 

func payMethodOptions(method: PaymentOptionsDetail) {
        //process the method       
}
<<<<<<< HEAD

=======
>>>>>>> fc5444bbca0ed88341e3766f01d529dac8946969
```