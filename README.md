The exported function takes three arguments:

1. A Common Form

2. An Array of fill-in-the-blank values

3. An options Object

The options object must contain:

1. A `numbering` property whose value is an [abstract numbering](https://npmjs.com/packages/abstract-numbering)

It may contain:

1. A `title` property whose value is a string

2. An `edition` property whose value is a string

3. A `hash` property whose value is `true` or `false`

4. A `markFilled` property whose value is `true` or `false`

The function returns a [JSZip](https://npmjs.com/packages/jszip) Object primed with `.docx` document data.
