# WhatsApp-Business-Chatbot

# Problem

Every business today is on WhatsApp.

Customers ask the same questions again and again:

1. What are your prices?
2. Do you deliver here?
3. Where’s my order?

And sometimes, they just want to chat freely or give feedback.

But replying to everyone manually is:

❌ Slow
❌ Boring
❌ Costly

💡 Solution

# I built a WhatsApp Business Chatbot using AWS + AI.

This chatbot can:

> Instantly reply to FAQs
> Handle customer orders
> Store every conversation for future insights
> Use AI to chat smartly with customers
> Send notifications back to users in real-time

So customers feel heard instantly and businesses save hours of manual work.

# How it works (Simple Flow)

> User sends a WhatsApp message
> The message is stored in Amazon S3 (like a mailbox for all chats)
> A Lambda function sorts the message
> If it’s an FAQ → it sends to a Smart Responder Lambda
> If it’s an order or free chat → it goes to AI Brain (Amazon Bedrock)
> Every conversation is saved in DynamoDB (like a history log)
> Finally, a reply is sent back instantly through SNS

# Architecture Diagram

![Architecture](WhatsApp%20Business%20Chatbot-architecture.png) 

# Why this is powerful

1. 100% automated replies (never keep your customer waiting)
2. Scales as your business grows
3. AI-powered (understands free chat too, not just fixed answers)
4. Saves cost, time, and builds trust with customers

# Real-World Impact

Imagine a small shop owner or an online seller.

Instead of checking WhatsApp all day, they now:
✅ Reply instantly to FAQs
✅ Manage orders automatically
✅ Get a system that grows with them

The owner can finally focus on business growth instead of typing all day.
