This is a [Next.js](https://nextjs.org/) template to use when reporting a [bug in the Next.js repository](https://github.com/vercel/next.js/issues) with the `app/` directory.

## Reproduction Steps

```bash
npm install
npm run build
```

open the browser at `http://localhost:3000` and check the source.

You will see that every class name looks like `veryVeryVeryVeryVeryVeryLongModuleName_footer__UEyfO`. This happens in DEV and PROD mode.