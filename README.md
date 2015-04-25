## nginx
Base Docker image containing Nginx running in Alpine Linux version 3.1.

This image contains a version of Nginx 1.6.2 that was specifically compiled 
with the --with-http_stub_status_module flag. Other than that this is identical
to the version of Nginx 1.6.2 that is available in the Alpine Linux package
repository.

    FROM centurylink/nginx:1.6.2
