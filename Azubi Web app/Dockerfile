FROM  php
# Copy the contents of the web app to the container
COPY ./workspace/web app azubi

# Set the working directory to the web app folder
WORKDIR /workspace/web app azubi

EXPOSE 8000
CMD ["php","-S","0.0.0.0:8000"]
