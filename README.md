# Module for REST FAQ 

## Permissions
Add `administer dom faq items` permission for people that should be able to manage both FAQs and FAQ categories.

## Manage
Page to manage FAQ items can be found on `admin/config/dom-faq`, and `admin/structure/taxonomy/manage/faq_category/overview` to manage categories.

## REST
FAQ items should be available on `GET api/dom-faq`, it's possible to filter by `categoryID` as well.
