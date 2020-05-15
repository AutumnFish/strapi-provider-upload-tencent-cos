# Strapi-Provider-Upload-Tencent-COS

A tencent cos provider plugin deved for strapi.

[COS Node.js SDK](https://cloud.tencent.com/document/product/436/8629)

[Region](https://cloud.tencent.com/document/product/436/6224)

[Useing a provider](https://strapi.io/documentation/3.0.0-beta.x/plugins/upload.html#using-a-provider)

Thanks [strapi-provider-upload-tencent](https://www.npmjs.com/package/strapi-provider-upload-tencent)



## Installation

```bash
npm i strapi-provider-upload-tencent-cos
```

Or use yarn

```bash
yarn add strapi-provider-upload-tencent-cos
```



## config

`./extensions/upload/config/settings.json`

```
{
  "provider": "tencent-cos",
  "providerOptions": {
    "accessKeyId": "Your KeyId",
    "secretAccessKey": "Your AccessKey",
    "region": "Your bucket region",
    "params": {
      "bucket": "Your bucket name"
    }
  }
}

```

