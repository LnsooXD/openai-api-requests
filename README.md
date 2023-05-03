# OpenAI API Request Samples

Some Request Examples for [OpenAI API](https://platform.openai.com/docs/api-reference/)
Official Playground: [https://beta.openai.com/playground](https://beta.openai.com/playground)

## Usage

1. Open this repository with IntelliJ IDEA (Ultimate Edition)
2. Make a copy of [http-client.env.json.example](./http-client.env.json.example) and rename to [http-client.private.env.json](./http-client.private.env.json).
3. Fill in your `OPENAI_API_KEY` key in [http-client.private.env.json](./http-client.private.env.json). If you belong to multiple organizations, you would need to specify the `OPENAI_ORGANIZATION_ID` as well.
4. Open one of the request files in [src](./src) and run it with `dev` environment.
5. Enjoy!

## Acknowledgement
Grateful to [betalgo/openai](https://github.com/betalgo/openai) for providing some [sample data]([sample data](https://github.com/betalgo/openai/tree/master/OpenAI.Playground/SampleData).
The OpenAI has some restrictions on the format of the request data, the [sample data](https://github.com/betalgo/openai/tree/master/OpenAI.Playground/SampleData) provided by [betalgo/openai](https://github.com/betalgo/openai) is very helpful.

## References
- [OpenAI API Reference](https://platform.openai.com/docs/api-reference/)
- [OpenAI Playground](https://beta.openai.com/playground)
- [HTTP Client plugin](https://www.jetbrains.com/help/idea/2023.1/http-client-in-product-code-editor.html)

## License
[MIT License](./LICENSE)