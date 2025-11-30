All my stuff around gentoo...

# repository
## eselect repository
### eselect-repository installieren (falls noch nicht vorhanden)
   ```bash
   sudo emerge --ask app-eselect/eselect-repository
   ```
### Repository hinzufügen
   ```bash
   sudo eselect repository add gentoo-repo git https://github.com/OliBerlin/gentoo-repo.git
   sudo emerge --sync gentoo-repo

   ```

Hinweis: Die genauen Befehle hängen von deiner eselect-repository-Version ab; siehe `eselect repository --help` für Details.
