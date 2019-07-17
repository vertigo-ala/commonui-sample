# commonui-sample

Sample custom commonui docker image for ALME (Atlas of Middle Earth)

Please notice the docker-compose workflow overrides CMD in order to copy html content over the already bundled content. This way we minimize the quantity of versioned files, preserve all the original static content and still have a productive working environment.

The need to preserve the original content is because I have absolutely no idea of what files are needed throughout ALA modules (css, js, img etc.).
