# Node.js Docker Official Image
FROM node
# Ensure your version of npm is up to date
RUN npm install -g npm \
# Install Yeoman and the generator for JavaScript
 && npm install -g yo generator-botbuilder
# Change to non-root user
USER node
# Set the working directory
WORKDIR /home/node
# Generate bot 
RUN yo botbuilder --noprompt
# Start bot
CMD cd my-chat-bot ; npm start
