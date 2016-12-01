# 0_CSD322_Lecture_UnderstandingMultiPartForms
##File Uploads
##Demonstrates Multipart Form Uploads (multipart/form-data)
###Part I - Introduction and html only solution
####Read this article for an introduction to multi-part form data
####https://docs.oracle.com/javaee/6/tutorial/doc/glraq.html
###Part II - JSF solution
####http://stackoverflow.com/questions/15074465/how-to-populate-hgraphicimage-value-with-image-content-from-database"
####http://showcase.omnifaces.org/components/graphicImage
####* Uploads are handled on the server using CDI managed bean (jsfclasses.ImagesController)
####* Images are stored in a mysql database.  See webroot\mysql for script to create database table
####* Uses omnifaces o:graphicImage tag to display image retrieved via the bean.
            
