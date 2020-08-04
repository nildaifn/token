# Please Stop
Do you want to cancel redundant GitHub workflows? Then this is the Action for YOU.
Do you want to specify which workflow to stop by the yaml file? Then this is the Action for YOU.
Do you want to cancel redundant builds on the same commit? Im working on it :D.

## Inputs

### `token`

**Required** Github Token with write access.

## Example usage

```yaml
uses: JoseThen/comment-pr@v1
with:
  token: ${{ github.token }}
```
