#===============================================================================
#  GIGA-CHAD WEB VULN SCANNER  (terminal-only, to save output run as ./giga_vulnscan.sh | tee your_filename.txt
#===============================================================================
#  A defensively-coded, layered scanning framework with:
#    - Quick & Full scan modes (Non-Aggressive / Aggressive)
#    - Installer for dependencies (apt + gem + go + git clone)
#    - Robust timeouts, error handling, safe-guards, and WAF-friendly defaults
#    - Clear “VULN!!!” findings with brief risk+context
#    - Optional remediation snippets (Cloudflare / Nginx / Apache)
#    - Zero output to disk (prints to terminal only)
#
#  USAGE:
#    Save as: giga_vulnscan.sh
#    chmod +x giga_vulnscan.sh
#    ./giga_vulnscan.sh
#
#  LEGAL:
#    *** ONLY scan assets you OWN or have explicit WRITTEN authorization to test. ***
#    Misuse may be illegal. You are responsible for complying with all laws.
#===============================================================================
