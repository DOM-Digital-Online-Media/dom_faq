# Module for REST FAQ 

## Permissions
Add `view|create|update|delete paragraph content faq` permission for people that should be able to manage FAQs.

## Manage
Page to manage FAQ items can be found on `admin/config/dom-paragraphs/faq`, and `admin/structure/taxonomy/manage/faq_category/overview` to manage categories.

## REST
FAQ items should be available on `GET api/dom-faq`, it's possible to filter by `categoryID` as well.
