# queue

The only code that talks to the job queue (SQS). Other modules send and receive jobs through this module, so the queue can be swapped later.

**Owns tables:** none

**Inside `internal/`:** sqs

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
