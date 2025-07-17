# Ansible Role: SourceGuardian

این Role کار نصب و بروزرسانی SourceGuardian loaders و  
اجرای CageFS را در سرورهای cPanel + LVE انجام می‌دهد.

## Usage

```yaml
- hosts: sourceguardian_targets
  become: true
  roles:
    - sourceguardian
