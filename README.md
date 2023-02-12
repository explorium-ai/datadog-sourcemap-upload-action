# Upload JavaScript Sourcemaps to Datadog

## Full Example usage

```yaml
- name: Upload JavaScript Sourcemaps to Datadog
  uses: explorium-ai/datadog-sourcemap-upload-action@main
  with:
    api-key: 12345abcdrg4rfg6hj92b34a82f113f
    path: /app/dist/
    service: frontend
    release-version: ${{ github.sha }}
    minified-path-prefix: https://cdn.mycompany.com
```