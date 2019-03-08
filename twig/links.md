Sylius Links in twig
======================

How to get path of one specific content :

Base
------------

**Home page**

`{{ path('sylius_shop_homepage') }}`

**Product**

`{{ path('sylius_shop_product_show', {'slug': app.request.get('slug'), '_locale':app.request.getLocale() }) }}`

**Taxons**

`{{ path('sylius_shop_product_index', {'slug': 'books', '_locale': configuration.request.locale}) }}`

**Cart**

`{{ path('sylius_shop_cart_summary') }}`

**Contact**

`{{ path('sylius_shop_contact_request') }}`


Bitbag CMS Plugin
------------

**FAQ**

`{{ path('bitbag_sylius_cms_plugin_shop_frequently_asked_question_index') }}`

**Specific CMS page**

`{{ path('bitbag_sylius_cms_plugin_shop_page_show', {'slug' : 'cgv'}) }}`
