# Grails 3 File Uploader Example

- This repo is based on an example presented on [site](http://grails.asia/grails-example-application-simple-document-management-system).

- Alternative approach is also provided in `DocumentController` commented as **New METHOD**.

> Note : It is not necessary to make a domain class. Domain class is used for displaying purpose in `list` view.

This is the most short and crisp method to file upload in grails 3.

> For Grails 2 refer docs of `file uploader` plugin.

> Note : You can also use:
```html
<form action="document/upload" method="POST" enctype="multipart/form-data">
  <input type="file" name="fileupload"/>
  <input type="submit" value="Upload File" />
</form>
```
in place of `<g:uploadForm>`.
