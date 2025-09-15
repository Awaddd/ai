

- [ ] press escape twice to rewind
- [ ] /memory to edit global and local memory files
- [ ] # to quickly add a memory
- [ ] /comapct
- [ ] /clear
- [ ] /exit & /resume to start over from one specific point


# Tips

- [ ] Avoid burdening ai with too much context i.e. if you want it to focus on a single component really well, break away somehow. i.e. through agents, or clearing context completely, or using compact
- [ ] Type think in your prompt to turn think mode on. Think varies in ability and token usage. think -> think hard -> think harder -> ultrathink
- [ ] Use plan mode
- [ ] Use custom commands i.e. /create-ui-component card | a card component with a subtle box and border, and a muted background colour
- [ ] Use context7 mcp server to ensure claude has access to latest docs
- [ ] Use playwright so claude can open a browser, navigate to a page, even summarise it etc
- [ ] Use subagents i.e. ui-reviewer. This can tap into playwright, see what a page looks like and then give feedback. Even mix it with the custom command, and iterate
	- [ ] sample prompt: Expert UI & UX engineer who reviews the UI & UX of React components in a browser using Playwright, takes screenshots, then offers feedback on how to improve the component in terms of visual design, user experience and accessibility

mcp
https://github.com/microsoft/playwright-mcp
https://github.com/upstash/context7
https://www.aitmpl.com/component/mcp/ios-simulator-mcp

Simple agents
https://www.aitmpl.com/component/agent/frontend-developer

Detailed Agents
https://github.com/wshobson/agents/blob/main/code-reviewer.md
https://github.com/wshobson/agents/blob/main/ui-ux-designer.md
https://github.com/wshobson/agents/blob/main/prompt-engineer.md
https://github.com/wshobson/agents/blob/main/payment-integration.md
https://github.com/wshobson/agents/blob/main/mobile-developer.md
https://github.com/wshobson/agents/blob/main/frontend-developer.md
https://github.com/wshobson/agents/blob/main/debugger.md
https://github.com/wshobson/agents/blob/main/content-marketer.md
https://github.com/wshobson/agents/blob/main/tutorial-engineer.md

