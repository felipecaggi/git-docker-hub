# initializes a new build stage and sets the Base Image for subsequent instructions
FROM php:7.1-apache

    # copies new files or directories from <src> and adds them to the filesystem of the container at the path <dest>
    COPY ./ /var/www/html

    # informs Docker that the container listens on the specified network ports at runtime
    EXPOSE 80/tcp

    # provide defaults for an executing container
    CMD ["apache2-foreground"] 


# Documentation of Docker instructions available at available at https://docs.docker.com/engine/reference/builder/
