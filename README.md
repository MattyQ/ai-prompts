# ai-prompts
Open-source AI prompts for creative, professional, and mundane tasks.

This repository exists to provide open-source, no-attribution prompts for
applications of AI such as ChatGPT, Bing Chat, Bard, and other generalized, generative
approaches.

Prompts are provided in individual files. This README contains tables and
brief descriptions of the prompts organized by category.

Categories:

- [Creative prompts](#creative-prompts)
- [Professional prompts](#professional-prompts)

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
        <a href="creative/storybook.md">Children's book - 500 words - ages 5 to 10</a>
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
      </td>
    </tr>
    <tr>
      <td>
        <a href="creative/writing-assistant.md">Writing assistant - fiction books</a>
      </td>
      <td>
        <ul>
          <li>
            ChatGPT (GPT-4 only)
          </li>
        </ul>
      </td>
      <td>
        <p>
          File: <a href="creative/writing-assistant.md"><code>./creative/writing-assistant.md</code></a>
        </p>
        <p>
          This prompt provides the AI with a list of steps to follow. The steps instruct the AI to generate a book based on instructions from the user. The book is generated chapter by chapter, paragraph by paragraph. On request, the assistant can return its memory in JSON format, and make changes to the memory.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <a href="creative/self-prompt.md">Self-prompt for surprising outcome</a>
      </td>
      <td>
        <ul>
          <li>
            ChatGPT
          </li>
        </ul>
      </td>
      <td>
        <p>
          File: <a href="creative/self-prompt.md"><code>./creative/self-prompt.md</code></a>
        </p>
        <p>
          This prompt asks the AI to generate a creative task for itself that might result in a surprising outcome. The AI will then use the generated prompt as input and perform the task.
        </p>
      </td>
    </tr>
  <tbody>
</table>

---

<h2 id="professional-prompts">Professional prompts</h2>

Prompts in the Professional category are generally for tasks related to business, research, and other professional needs.

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
        <a href="professional/convert-document-to-json.md">Convert document to JSON schema</a>
      </td>
      <td>
        <ul>
          <li>
            ChatGPT
          </li>
        </ul>
      </td>
      <td>
        <p>
          File: <a href="professional/convert-document-to-json.md"><code>./professional/convert-document-to-json.md</code></a>
        </p>
        <p>
          This prompt asks the AI to convert a given document into a JSON schema with the following format: { "title": "string", "author": "string", "publication_date": "number (formatted as YYYYMMDD)", "access_date": "number (formatted as YYYYMMDD)", "summary": "string" }. The "publication_date" should be the date the document was originally published, and "access_date" should be the date the AI received the document. The AI should also write a summary of the document and output the JSON into a code box.
        </p>
      </td>
    </tr>
  <tbody>
</table>
