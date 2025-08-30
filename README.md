Forked for personal use.

---

# tiller

<https://yossarian.net/til/> for an example of a Tiller-generated website,

## Local development

The easiest way to iterate on a `tiller` managed website locally is
with `--dev` and a local HTTP server:

```bash
tiller --dev
python -m http.server -d site/ 1337 # or some gazillion way to `serve`, `miniserve`, so on.
```
