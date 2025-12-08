---
title: "Week 10 Worklog"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Learn about Amazon SQS (Simple Queue Service) - message queue service
* Practice with SQS demos to understand how it works
* Deploy SQS to project for asynchronous processing
* Test SQS integration between Lambda functions
* Ensure sequential image processing with SQS
* Attend AWS Cloud Mastery Series #1 event

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - Learn about SQS | 11/10/2025 | 11/10/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Learn more about SQS <br> - Test SQS demos | 11/11/2025 | 11/11/2025 | <https://cloudjourney.awsstudygroup.com/> <br> <https://000083.awsstudygroup.com/vi/> |
| 4   | - Start deploying SQS to project | 11/12/2025 | 11/12/2025 | |
| 5   | - Test SQS between lambda functions in project | 11/13/2025 | 11/13/2025 | |
| 6   | - Test sequential image processing with SQS | 11/14/2025 | 11/14/2025 | |
| 7   | - Attend AWS Cloud Mastery Series #1 event | 11/15/2025 | 11/15/2025 | <https://luma.com/imkevnow?tk=v3n25y> |


### Week 10 Achievements:

* **Mastered Amazon SQS:**
  * Understood message queue and asynchronous processing
  * Learned differences between Standard Queue and FIFO Queue
  * Mastered concepts:
    * Message retention period
    * Visibility timeout
    * Dead Letter Queue (DLQ)
    * Long polling vs Short polling
    * Message deduplication
  * Understood use cases: decoupling microservices, buffering requests, load leveling

* **Practiced with SQS demos:**
  * Tested creating and configuring SQS queues
  * Sent and received messages via console and CLI
  * Experimented with visibility timeout
  * Tested Dead Letter Queue functionality
  * Evaluated performance with different queue types

* **Successfully deployed SQS to project:**
  * Integrated SQS into serverless architecture
  * Created SQS queues for asynchronous image processing
  * Configured Lambda triggers from SQS
  * Implemented message producers and consumers
  * Set up IAM permissions for SQS access

* **Integrated SQS with Lambda functions:**
  * Tested message processing flow between Lambda functions
  * Ensured error handling and retry logic
  * Implemented Dead Letter Queue for failed messages
  * Monitored queue metrics: messages in flight, age of oldest message
  * Optimized batch size and concurrency settings

* **Ensured sequential image processing:**
  * Used FIFO queue to ensure processing order
  * Implemented message group ID for ordering
  * Tested with multiple images upload
  * Verified correct processing order
  * Handled edge cases and race conditions

* **Attended AWS Cloud Mastery Series #1:**
  * Learned best practices from AWS experts
  * Networked with AWS community
  * Updated knowledge about new services
  * Applied insights to project
