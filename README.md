# Metapackage - Hyvä AI Providers
This metapackage provides access to all Hyvä AI providers.

## Installation

### For Hyvä license holders

1. Install via composer
    ```
    composer require hyva-themes/magento2-ai-providers
    ```
1. Run `bin/magento setup:upgrade`

### For contributions

1. Install via composer
    ```
    composer config repositories.hyva-themes/magento2-ai-providers git git@gitlab.hyva.io:hyva-themes/ai/metapackage-ai-providers.git
    composer config repositories.hyva-themes/magento2-module-ai git git@gitlab.hyva.io:hyva-themes/ai/module-ai.git
    composer config repositories.hyva-themes/magento2-module-ai-deep-l git git@gitlab.hyva.io:hyva-themes/ai/module-ai-deep-l.git
    composer config repositories.hyva-themes/magento2-module-ai-gemini git git@gitlab.hyva.io:hyva-themes/ai/module-ai-gemini.git
    composer config repositories.hyva-themes/magento2-module-ai-open-ai git git@gitlab.hyva.io:hyva-themes/ai/module-ai-open-ai.git
   
    composer require hyva-themes/magento2-ai-providers:dev-main --prefer-source
    ```
1. Run `bin/magento setup:upgrade`

## Documentation
Coming soon.
