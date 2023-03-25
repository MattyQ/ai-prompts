# ai-prompts
Open-source AI prompts for creative, professional, and mundane tasks.

This repository exists to provide open-source, no-attribution prompts for
applications of AI such as ChatGPT, Bing Chat, Bard, and other generalized
approaches.

Prompts are provided in individual files. This README contains tables and
brief descriptions of the prompts organized by category.

Categories:

- [Creative prompts](#creative-prompts)

---

<h2 id="creative-prompts">Creative prompts</h2>

Prompts in the Creative category are generally for tasks like writing, editing, generating music lyrics and chord notation, generating prompts for image models, and other related needs.

<table>
  <thead>
    <tr>
      <th>
        Summary
      </th>
      <th>
        Validated on
      </th>
      <th>
        Description
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="creative/storybook.md">Children's book - 500 words - ages 5 to 10 (v1)</a>
      </td>
      <td>
        <ul>
          <li>
            ChatGPT
          </li>
          <li>
            Bing Chat
          </li>
        </ul>
      </td>
      <td>
        <p>
          File: <a href="creative/storybook.md"><code>./creative/storybook.md</code></a>
        </p>
        <p>
          This prompt asks the AI to return a children's book that is fun and creative, around 500 words in length, and appropriate for children ages 5 to 10.
        </p>
        <p>
          Observations:
        </p>
        <ul>
          <li>
            <p>
              ChatGPT demonstrated a tendancy to prioritize "appropriate for children ages 5 to 10," and rejected prompts that it percieved (so to speak) to be inappropriate. A practical example: my youngest suggested a prompt where a popular electric mouse farts so much that it knocks out and eventually asphyxiates everyone in the world. I assumed that ChatGPT was averse to the death-by-fart bit, and so we rewrote the prompt. After some experimentation, we determined that it wasn't an issue with the knocking out or death, but rather that the prompt included a statement that the electric mice "didn't even notice" what had happened.
            </p>
            <p>
              Solution: Instructing ChatGPT to itself remove the material it found inappropriate unblocked ChatGPT so it could write a story based on the prompt. We'd attempted to manually curate the prompt ourselves, but in the end it was simpler to give ChatGPT that broader autonomy in the context of the conversation.
            </p>
          </li>
        </ul>
      </td>
    </tr>
  <tbody>
</table>
