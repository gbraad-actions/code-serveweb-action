Code serve web action
=====================


This action runs Code in the served mode that sets up `http://[IP]:8000` for your browser.

```yaml
    - name: Code serve web
      if: ${{ failure() }}
      uses: gbraad-actions/code-serveweb-action@v1
```

> [!NOTE]
> This actions relies on a service like Tailscale to expose the serveweb to a reachable endpoint
