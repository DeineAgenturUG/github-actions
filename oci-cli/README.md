# oci-cli-action
Action for installing oci-cli (Oracle Cloud Infrastructure CLI)


# Example usage
```yaml
- name: Install oci-cli
  uses: DeineAgenturUG/github-actions/oci-cli@main
  with:
    user: "${{ secrets.OCI_USER }}"
    fingerprint: "${{ secrets.OCI_FINGERPRINT }}"
    tenancy: "${{ secrets.OCI_TENANCY }}"
    region: "${{ secrets.OCI_REGION }}"
    api_key: |
      ${{ secrets.OCI_API_KEY }}
    verbose: true
```

## Credits
This is a work that was inspired by https://github.com/bytesbay/oci-cli-action
