## Magento 2 Spanish Spain Language Pack

### Download and install manually

To download and install Spanish pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/jrosell/es_es/archive/master.zip)

#### Step 1: Unzip and upload

Create `app/i18n/jrosell/`
Unzip `es_ES-master.zip` there
Rename to `app/i18n/jrosell/es_es/`

#### Step 2: Flush cache

php bin/magento cache:clean
php bin/magento cache:flush

## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Spanish language pack}}](https://i.imgur.com/aPSUA0l.png)

You may need to deploy:
`php bin/magento setup:static-content:deploy es_ES`

References:
- https://www.mageplaza.com/magento-2-spanish-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/