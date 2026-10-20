<div align="center">

# Cognitive Interface Lab

**Bicycle for the Mind.** We build interfaces for thinking with AI, not just chatting with it.

[Try Trilix](https://trilix.theenigmax.com) · [core on GitHub](https://github.com/Cognitive-Interface-Lab/core) · [Blog](https://trilix.theenigmax.com/blog) · [YouTube](https://www.youtube.com/@cognitive-interface-lab) · [Product Hunt](https://www.producthunt.com/products/trilix-chat)

</div>

---

## Trilix

Trilix turns linear AI chats into a **branchable reasoning graph**. Every prompt is a
node on a canvas. Fork any answer, run branches side by side on different models, and
trace exactly which context produced which result.

| | |
| --- | --- |
| **Ask** | Every question starts a graph. Answers come back as structured output: summary, confidence, actions, risks, next steps. |
| **Branch** | Drag from any answer to fork a new line of thought. Each node can run a different model: OpenAI, Anthropic, Gemini, OpenRouter, Cloudflare. |
| **Explore** | Run several branches at once and they stream in parallel. |
| **Trace** | Each branch carries only its own lineage as context, with no bleed between siblings. Model, latency, tokens, and cost are logged for every run. |

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://youtu.be/_j71Lxw_zJk">
        <img src="https://i.ytimg.com/vi/_j71Lxw_zJk/hqdefault.jpg" alt="Trilix demo video" width="100%">
      </a>
      <br><b>Demo:</b> from scattered AI chats to one reasoning graph
    </td>
    <td align="center" width="50%">
      <a href="https://youtu.be/urIW4ONG8nM">
        <img src="https://i.ytimg.com/vi/urIW4ONG8nM/maxresdefault.jpg" alt="Trilix 60-second tutorial" width="100%">
      </a>
      <br><b>Tutorial:</b> Trilix in 60 seconds
    </td>
  </tr>
</table>

**Get started:** open [trilix.theenigmax.com](https://trilix.theenigmax.com), sign in with
GitHub or Google for free daily model runs, or
[connect your own provider](https://trilix.theenigmax.com/blog/connect-ai-models-to-trilix).

## core

[core](https://github.com/Cognitive-Interface-Lab/core) is the open-source TypeScript
backbone behind Trilix, under the MIT license. It gives your product one interface to many
model providers (OpenAI, Anthropic, Gemini, Azure OpenAI, OpenRouter, Cloudflare, Groq,
Vercel AI Gateway, Ollama, or any OpenAI-compatible server) with fallback when one fails,
plus tools and MCP, a conversation graph you can branch and replay, and an HTTP API.

Use it from your terminal, inside your own app, or let your website pair with core on a
visitor's computer so their keys never leave it.
[Three ways to use it](https://github.com/Cognitive-Interface-Lab/core#three-ways-to-use-it).

## Where we're going

**Tool → System → Platform → Protocol.** Today Trilix is a workspace for individuals.
Next come shared graphs for small teams, then an SDK so other products can embed the
branchable workspace, and eventually an open protocol for human–AI interfaces where every
step is typed, versioned, and replayable. core is the first open piece of that, available
today.

## Get involved

- core: issues and pull requests are welcome at [github.com/Cognitive-Interface-Lab/core](https://github.com/Cognitive-Interface-Lab/core)
- Feedback and bug reports: [trilix.theenigmax.com/support](https://trilix.theenigmax.com/support)
- Contact: alireza.ataee01@gmail.com
- If Trilix is useful to you, an upvote on [Product Hunt](https://www.producthunt.com/products/trilix-chat) helps others find it.
