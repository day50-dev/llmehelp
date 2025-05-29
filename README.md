<p align="center">
  <img src=https://github.com/user-attachments/assets/929421a7-ef83-4ca6-b0d8-7c8942b5ce41>
  <br/>
  <strong>A tmux-based ai assistant</strong>
</p>

Simple installer:

    curl day50.dev/sidechat | sh

An llm intervention in your little terminal with suppport for adding screenshots, command output, cycling pane focus, turning off and on pane capturing, adding external context and more, all sitting agnostically on top of tmux so there's no substantive workflow change needed. You can just beckon your trusty friend at your leisure.


[demo.webm](https://github.com/user-attachments/assets/9e8dd99a-510b-4708-9ab5-58b75edf5945)

## There's an agentic mode. We call it DUI. Enable it with `/dui`.
![2025-05-15_18-50](https://github.com/user-attachments/assets/d1da6063-b450-49f8-863d-fcf0c32647fc)



You should also use `sc-add` which can pipe anything into the context. Here's an example:
![out](https://github.com/user-attachments/assets/62318080-9d67-41de-921b-976ad61e1122)


Once you're in there's a few slash commands. Use `/help` to get the current list.

Multiline is available with backslash `\`, just like it is at the shell

![2025-05-01_13-38](https://github.com/user-attachments/assets/e57ea643-cb63-4727-9901-e15109b81adb)


Here's some screenshots of how it seamlessly works with [Streamdown's](https://github.com/day50-dev/Streamdown) built in `Savebrace` feature and how it helps workflow.
![2025-04-26_18-45](https://github.com/user-attachments/assets/a81cbcea-cb15-46d9-92ac-5430238b2b85)

![2025-04-26_18-49](https://github.com/user-attachments/assets/c8b98e30-cd09-47bc-b751-02a929a82703)

![2025-04-26_18-49_1](https://github.com/user-attachments/assets/c752f94f-b780-4a8b-b597-1ce62b2bdb78)

Also you don't need `tmux`! Often you'll be doing things and then realize you want the talk party and you're not in tmux.

That's fine! If you use DAY50's [streamdown](https://github.com/day50-dev/Streamdown),  `sc-picker` works like it does inside tmux. You can also `sc-add` by id. It's not great but you're not locked in. That's the point!

**Note**: This used to be the home of many tools. They've been moved to [llm-incubator](https://github.com/day50-dev/llm-incubator)
