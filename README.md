# NIGOV message list
**Version 1.0.0** 

> This component is currently experimental because more research is needed to validate it.

## When to use it
Use the message list component to show a conversation between the users of a case management system.

## How it works
The message list component is a styled unordered list with each message contained in a list item.

'''
<h2 id="messages" class="govuk-heading-l">Messages</h2>
<ul class="govuk-list nigov-message" aria-labelledby="messages">
    <li id="message-1" tabindex="-1">
        <h3 class="govuk-heading-s nigov-message--heading">
            <span class="govuk-body-s nigov-message--number">Message 2 of 2</span>
            <span class="govuk-visually-hidden"> from </span>Peter Smith, The Executive Office
            <span class="govuk-visually-hidden"> on </span><span class="govuk-body nigov-message--date">12 February 2022
                at 15:44</span>
        </h3>
        <dl class="govuk-summary-list">
            <div class="govuk-summary-list__row">
                <dt class="govuk-summary-list__key">
                    Message
                </dt>
                <dd class="govuk-summary-list__value">
                    <p class="govuk-body">
                        Thanks David</p>
                    <p class="govuk-body">Peter</p>
                    <p class="govuk-body nigov-message--replylink">In reply to: <a href="#message-1"
                            class="govuk-link">David Smith, Department of Finance</a></p>
                </dd>
            </div>
        </dl>
        <button class="govuk-button govuk-button--secondary" data-module="govuk-button">
            Reply to message 2
        </button>
    </li>
</ul>
'''

