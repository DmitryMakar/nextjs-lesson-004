# nextjs-lesson-004
Learn NextJS. Lesson 4. Creating Layouts &amp; Pages

The corresponding lecture: https://youtu.be/CivZ59Qckdk?list=UULFYKBw6nEou6ga4qdGYfJ9IQ

Update from lecture 7: Installing nexxt-app into Docker
1. Install Docker on your host
2. Uncommment output: "standalone" in next.config.mjs
3. From the package folder build the nexxtapp image:
   docker build -t nexxtapp . 
4. Start the nexxtapp container in the detached mode and using port 3000
   docker run -p 3000:3000 -d nexxtapp
5. Visit the localhost:3000 to verify it works
 
