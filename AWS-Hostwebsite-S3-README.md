<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Host a Website on Amazon S3

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-host-a-website-on-s3)

**Author:** Albert  
**Email:** tapcyberx@gmail.com

---

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Introducing Today's Project!

### Tools and concepts

Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance.

### Project reflection

To create a Website Host

---

## How I Set Up an S3 Bucket

it took me a couple minutes.

I picked N. Virginia us-east-1 because from my perspective is more global from the location there I'm at.

This means, no two buckets can share the same name, ensuring each bucket can be uniquely addressed via URL. 

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-host-a-website-on-s3_ba6d42ad)

---

## Upload Website Files to S3

### index.html and image assets

I uploaded two files to my S3 bucket - they were index.html and zip folder. 



Both files are necessary for this project as object for compouse the website 

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-host-a-website-on-s3_a265af88)

---

## Static Website Hosting on S3

 Is a services that provides the storage and infrastructure needed to make a website accessible on the internet, allowing users to access and view it

To enable website hosting with my S3 bucket, I have to go properties and (edit) static website hosting hit enable.   

An ACL is contains rules that grant or deny access to certain digital environments

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-host-a-website-on-s3_c22c54c0)

---

## Bucket Endpoints

Once static website is enabled, S3 produces a bucket endpoint URL, which is allows you to access and view the content of a static website hosted in an Amazon S3 bucke

When I first visited the bucket endpoint URL, I saw 403 Forbidden (error) The reason for this error was the content for this site is still private.

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-host-a-website-on-s3_22ce4daf)

---

## Success!

To resolve this connection error, It was kind of challenge for me because it get stuck in the same error. My simple mistake after rewacthed the vide trying to figure out the solution, when I save the html file I wrote doble index.html.html aws bucket

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Bucket Policies

---

---
