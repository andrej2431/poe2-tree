# Path of Exile 2 - Skill Tree

This is a scuffed version of the Path of Exile 2 skill tree with data extracted from videos and screenshots. It's a community project so feel free to contribute.

# Contribute

If you want to contribute to the project there are a few ways to help

- Finding new sources
- Transcribing nodes from the mapped sources
- Improve the UI/UX

## Finding new sources

If you found a new source that is not listed here, please open an issue with the link to the video or screenshot.

## Transcribing nodes

Adding information nodes is quite simple

1. Open the skill tree and hover the mouse over the node you want to transcribe, it will show the node id if it has not been transcribed yet.

2. Go to the `src/data/nodes_desc.json` and search for the node id and edit the entry with the information you found.

Example:

```json
{
  ...
  "N152": {
    "name"": "Name of the node",
    "stats": [
      "First line of stats",
      "Second line of stats"
    ]
  },
  ...
}
```

3. Validate that you change the correct entry

4. Add the source to the list of mapped sources, if its a screenshot make sure to add it to you pull request

5. Open a Pull Request

## Improving the UI/UX

The UI/UX is quite basic and can be improved in many ways, if you have any ideas feel free to open an issue or a pull request.

# Mapped Sources

## Dreamcore Youtube

- [Int Area](https://www.youtube.com/watch?v=tI0xJb1HEYw)

# Sources to map

## Dreamcore Youtube

- [Int/Dex Area](https://www.youtube.com/watch?v=aTi9fF6fU24)
- [Dex Area](https://www.youtube.com/watch?v=6zj3X3Zw8W4)
- [Dex/Str Area](https://www.youtube.com/watch?v=6zj3X3Zw8W4)
- [Str Area](https://www.youtube.com/watch?v=6zj3X3Zw8W4)
- [Str/Int Area](https://www.youtube.com/watch?v=6zj3X3Zw8W4)

## For Developers

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

### Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.