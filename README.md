# magento2-simplest-module
Magento2 module basic structure

1 Create namespace folder

/app/code/CosmoCommerce

2 Create module folder

/app/code/CosmoCommerce/Demo

3 Create module config folder

/app/code/CosmoCommerce/Demo/etc

4 Create module registration file

/app/code/CosmoCommerce/Demo/registration.php

\Magento\Framework\Component\ComponentRegistrar::register(
\Magento\Framework\Component\ComponentRegistrar::MODULE,
'CosmoCommerce_Demo',
__DIR__
);

5 Create module config file

/app/code/CosmoCommerce/Demo/etc/module.xml

<?xml version="1.0"?>
<config xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="../../../../../lib/internal/Magento/Framework/Module/etc/module.xsd">
<module name="CosmoCommerce_Demo" setup_version="1.0.0">
<sequence>
<module name="Magento_Backend"/>
</sequence>
</module>
</config>

 

 

Code download

https://github.com/cosmocommerce/magento2-simplest-module
