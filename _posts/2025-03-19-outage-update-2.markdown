---
layout: clean
title: "Outage Update - Restoration Quote"
date: 2025-03-19 03:05:00 -0500
categories: outage update
markdownlint:
  disable: ["MD033"]  # Disable inline HTML warning
---

<div style="max-width: 800px; margin: 0 auto; padding: 20px;">
    <div style="background-color: #cce5ff; border: 1px solid #b8daff; padding: 20px; border-radius: 5px; margin-bottom: 20px;">
        <h2 style="color: #004085; margin-top: 0;">🛑 Update Summary</h2>
        <p>After digging deeper it turns out the issue is with the data upstream provider. They are saying the issue with their network will be resolved by 7:00pm CST. There is nothing we are able to do... this is a nation wide outage.
        </p>
        <p><strong>Time Identified:</strong> 4:30 AM CST</p>
    </div>

    <div style="background-color: #e2e3e5; border: 1px solid #d6d8db; padding: 20px; border-radius: 5px; margin-bottom: 20px;">
        <h2 style="color: #383d41; margin-top: 0;">⚡ Current Actions</h2>
        <ul style="margin: 0; padding-left: 20px;">
            <li>Working with data center team to correct routing tables</li>
            <li>Implementing temporary failover to backup routes</li>
            <li>Estimated resolution time: 16 hours</li>
        </ul>
    </div>

    <div style="background-color: #d4edda; border: 1px solid #c3e6cb; padding: 20px; border-radius: 5px;">
        <h2 style="color: #155724; margin-top: 0;">✅ Service Status</h2>
        <ul style="margin: 0; padding-left: 20px;">
            <li>Main Website: 🛑 Offline - Network Provider Issue</li>
            <li>Online Banking: ✅ Fully Operational</li>
            <li>Mobile App: ✅ Fully Operational</li>
        </ul>
    </div>

    <div style="margin-top: 20px; color: #666; font-size: 0.9em;">
        <p>We apologize for any inconvenience and appreciate your patience as we wait for the network provider to resolve this issue.</p>
        <p>Last Updated: {{ page.date | date: "%B %d, %Y at %I:%M %p" }} CST</p>
    </div>
</div>
