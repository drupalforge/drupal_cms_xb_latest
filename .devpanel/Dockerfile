ENV COMPOSER_HOME="${HOME}/.config/composer"
USER root
RUN COMPOSER_HOME=/root/.config/composer composer selfupdate -n
USER ${USER}
