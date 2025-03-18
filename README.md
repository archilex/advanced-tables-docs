# Advanced Tables v3 (formerly Filter Sets)

![Advanced Tables with View Manager](https://user-images.githubusercontent.com/6097099/269182900-f3226af9-8e0c-4895-98e6-58499a76de7f.png)

## Introduction

Advanced Tables (formerly known as Filter Sets) is a premium plugin for [Filament](https://filamentphp.com/) that supercharges your tables with powerful features like user customizable views, enhanced filter tabs, reorderable columns, convenient view management, filter builder, and more. 

### Video

Check out a short video of some of the powerful features included in Advanced Tables
[![Youtube video](https://user-images.githubusercontent.com/6097099/269337282-39ae1c24-eb4c-4d0b-9c88-11fcf14297ef.png)](https://www.youtube.com/watch?v=_vhVHiBzqrs)

### Demo (New)

See all the functionality that Advanced Tables has to offer in an interactive demo. It also includes a Configuration Playground so you can see many of the configuration options you can use to adapt the plugin to your needs.

[Visit the Demo](https://advancedtables.com/demo)

### About

At its core, Advanced Tables allows you to combine filters, grouping, toggled columns, and more into custom views that are just one click away. Users no longer have to rebuild their views each time they need to focus on a certain subset of their data. Advanced Tables gives your users fast access to the information they need.

With Advanced Tables, views can be set up in advance by the developer or they can be created on-the-fly by your end-users using Quick Save. And with Advanced Table’s View Manager, your users will be able to conveniently create, apply, edit, share, and sort their views right from the resource or table.

Best of all, Advanced Tables works with *all* of your Filament tables including Resource Tables, Relation Managers, Table Widgets, and standalone Table Builder.

### Features

- Allow your users to save their filters, toggled columns, grouping, and more in customizable [User Views](#user-views)
- Developers can create [Preset Views](#preset-views) in code and deploy them for their clients
- (New) Preset Views can also include [filters](#applying-filters-new), [grouping](#applying-default-grouping-new), [toggled columns](#toggling-and-reordering-columns-new), and [column order](#toggling-and-reordering-columns-new)
- (New) The [Quick Save](#quick-save-new) button means saving custom views is just one click away
- (New) Enhance your tables with [Column Reordering](#reordering-columns)
- (BETA) [Managed Default Views](#managed-default-views-beta)
- (BETA) Quickly access your filters with [Advanced Indicators](#advanced-indicators-beta)
- (BETA) Sort by multiple table columns with [Multi Sort](#advanced-indicators-beta)
- (New) Create powerful queries with [Advanced Filter Builder](#advanced-filter-builder-new)
- Easily access views in the [Favorites Bar](#favorites-bar)
- (New) Sort, favorite, and edit views on the table using the [View Manager](#view-manager-new)
- (New) [SlideOver](#displaying-as-a-slideover), [modal](#displaying-as-a-modal), and dropdown options
- (New) Supports Multi-tenancy
- Choose from six different [themes](#themes)
- (New) Table loading [skeleton overlay](#table-loading-indicators-new)
- Includes a [User Views Resource](#user-views-resource) so your admins can manage all user views
- Users can make their User Views [publicly](#making-a-user-view-public) available to all users
- Easily [create and export](#create-and-export-reports) reports from your customized views with [Excel Export](https://filamentphp.com/plugins/pxlrbt-excel)
- Admins can create [global favorite views](#enabling-making-a-user-view-a-global-favorite) that will appear for all users
- Powerful [policy integration](#authorization) gives you complete control
- (New) Includes an [approval system](#approving-public-and-global-favorite-user-views-new) for User Views
- More than 60 configuration options to completely customize Advanced Tables to your needs
- Supports [Panel Resource Tables](https://filamentphp.com/docs/3.x/panels/resources/getting-started), [Relation Managers](https://filamentphp.com/docs/3.x/panels/resources/relation-managers#creating-a-relation-manager), [Table Widgets](https://filamentphp.com/docs/3.x/panels/dashboard#table-widgets), and [Standalone Table Builder](https://filamentphp.com/docs/3.x/tables/installation)
- Full support for dark mode
- Support for translated filter indicators

### Screenshots

Favorites Bar
![Advanced Tables with Favorites Bar](https://user-images.githubusercontent.com/6097099/269182896-9f621ed0-82e5-4ff2-af5b-f20e4000d545.png)

View Manager (New)
![Advanced Tables with View Manager](https://user-images.githubusercontent.com/6097099/269182900-f3226af9-8e0c-4895-98e6-58499a76de7f.png)

Quick Save (New)
![Advanced Tables with Quick Save](https://user-images.githubusercontent.com/6097099/269182904-18172c1a-9ad9-4ffa-9771-cea8a97db6a1.png)

Column Reordering (New)
![Advanced Tables with Column Reordering](https://user-images.githubusercontent.com/6097099/269182908-0ed8f362-7d65-4c0d-ad69-37a678577e22.png)

User Views Resource with Approval System (New)
![User Views Resource with Approval System](https://user-images.githubusercontent.com/6097099/269182912-4f28b518-a290-4a07-871b-b68497daf993.png)

View Manager in Table Toolbar (New)
![View Manager in Table Toolbar](https://user-images.githubusercontent.com/6097099/269182929-97b74164-56dd-45d1-aec0-b36368dc73f5.png)

Dark mode
![Dark mode](https://user-images.githubusercontent.com/6097099/269184198-423a38ae-c278-4460-a486-b4cc4a138fa6.png)

#### Themes

Github theme (New)
![Github theme](https://user-images.githubusercontent.com/6097099/269182896-9f621ed0-82e5-4ff2-af5b-f20e4000d545.png)

Filament theme (New)
![Filament theme](https://user-images.githubusercontent.com/6097099/269182916-60f0e6c8-dd54-4047-9e61-06aa127a743a.png)

Links theme
![Links theme](https://user-images.githubusercontent.com/6097099/269182918-21e970ca-bc0c-4590-bc9d-29d1af4ce975.png)

Links Simple theme
![Links Simple theme](https://user-images.githubusercontent.com/6097099/269182928-72568680-a345-4b3c-96d9-7e26f4523477.png)

Tabs theme
![Tabs theme](https://user-images.githubusercontent.com/6097099/269182921-008e14d8-50a8-46ef-bfbf-d94d1d2d63ce.png)

Tabs Simple theme
![Tabs Simple theme](https://user-images.githubusercontent.com/6097099/269182925-2b20d0cf-ee71-4a19-98ea-9b5f11174a39.png)

## Installation

Thank you for purchasing Advanced Tables!

Below you'll find extensive documentation on installing and using this plugin. Of course, if you have any questions, find a bug, need support, or have a feature request, please don't hesitate to reach out to me at advancedtables@gmail.com.

### Requirements

Advanced Tables requires `PHP 8.1+`, `MySQL 5.7.8+` or `Postgres`, `Filament 3.2.118+`, and `Laravel 10+`.

> Advanced Tables v1 is fully compatible with `Filament v2`. After purchasing a license here, please refer to the [Filter Sets v1](https://filamentphp.com.test/plugins/kenneth-sese-advanced-tables?v=v1#documentation) documentation for installation and usage instructions.

### Activating your license on AnyStack

AdvancedTables uses [AnyStack](https://anystack.sh) to handle payment, licensing, and distribution.

During the purchasing process, AnyStack will provide you with a license key. You will also be asked by AnyStack to activate your license by providing a `domain`. This is usually the domain of where your final project will live. You’ll use this same domain to install locally and in production. Once you have provide a domain, your license key will be activated and you can proceed with [installing with composer](#installing-with-composer) below. 

> Tip: If you missed this step, or if you need to add additional domains for other projects, you can access the activation page by going to [Transactions](https://account.anystack.sh/transactions) in your AnyStack account and then clicking `View details` on the Advanced Tables product. 

> Tip: You will need *both* your `license key` and your `domain` to authenticate when you install the package with composer. 

### Installing with Composer

To install Advanced Tables you'll need to add the package to your `composer.json` file:

```bash
{
    "repositories": [
        {
            "type": "composer",
            "url": "https://filament-filter-sets.composer.sh"
        }
    ],
}
```

> Advanced Tables was formerly named Filament Filter Sets, but for compatibility with previous versions, the repository has maintained its original name.

Once the repository has been added to your composer.json file, you can install Advanced Tables like any other composer package using the composer require command:

```bash
composer require archilex/filament-filter-sets
```

Next, you will be prompted to provide your username and password. 

```bash
Loading composer repositories with package information
Authentication required (filament-filter-sets.composer.sh):
Username: [licensee-email]
Password: [license-key]
```

Your username will be your email address and the password will is your license key, followed by a colon (:), followed by the domain you are activating. For example, let's say we have the following email and license activation:

- Contact email: **my_email@gmail.com**
- License key: **8c21df8f-6273-4932-b4ba-8bcc723ef500**
- Activation fingerprint: **my_domain.com**

You will need to enter the above information as follows when prompted for your credentials:

```bash
Loading composer repositories with package information
Authentication required (filament-filter-sets.composer.sh):
Username: my_email@gmail.com
Password: 8c21df8f-6273-4932-b4ba-8bcc723ef500:my_domain.com
```

The license key and fingerprint should be separated by a colon (:). 

> Tip: If you get a `402 error`, most likely you forgot to add the colon and fingerprint.

### Setting up Advanced Tables in Filament Panels (including Relation Managers, Table Widgets, and Panel Pages)

*If using Filament's standalone Table Builder, please refer to the [Filament Table Builder setup instructions](#setting-up-advanced-tables-in-filament-table-builder)*

1. Publish and run the migrations

    > Important: If you are using a User class other than Laravel's default `User::class` or a user's table other than Laravel's default `users` you should [update these configurations](#configuring-the-userclass) **before** migrating.

    ```bash
    php artisan vendor:publish --tag="advanced-tables-migrations"
    php artisan migrate
    ```

2. Publish the language files

    Optionally, you may publish the language files:

    ```bash
    php artisan vendor:publish --tag="advanced-tables-translations"
    ```

3. Add Advanced Tables to your Filament Panel

    Add Advanced Tables to a panel by instantiating the plugin class and passing it to the `plugin()` method of the configuration:

    ```php
    use Archilex\AdvancedTables\Plugin\AdvancedTablesPlugin;
    
    public function panel(Panel $panel): Panel
    {
        return $panel
            ->plugins([
                AdvancedTablesPlugin::make()
            ])
    }
    ```

4. Add the `HasViews` trait to your `User::class`
    
    ```php
    use Archilex\AdvancedTables\Concerns\HasViews;

    class User
    {
        use HasViews;
    }
    ```

5. Integrate Filter Set's Tailwind and css files

    Filament v3 recommends developers [create a custom theme](https://filamentphp.com/docs/3.x/panels/themes#creating-a-custom-theme) to better support a plugin's additional Tailwind classes. After you have created your custom theme, add Advanced Tables' views to your *new theme's* `tailwind.config.js` file usually located in `resources/css/filament/admin/tailwind.config.js`:

    ```js
    content: [
        ...
        './vendor/archilex/filament-filter-sets/**/*.php',
    ],
    ```

    Next, import Advanced Tables's custom stylesheet into your theme's css file:

    ```css
    @import '../../../../vendor/archilex/filament-filter-sets/resources/css/plugin.css';
    ```

6. Compile

    Next, compile your theme:

    ```bash 
    npm run build
    ```

    Finally, run the Filament upgrade command:
    
    ```bash
    php artisan filament:upgrade
    ```

7. Setting up tenancy

    If you are installing Advanced Tables into a multi-tenancy application, please refer to the separate instructions to [set up multi-tenancy](#multi-tenancy).

After you've successfully installed Advanced Tables, you may review the [Getting Started guide](#getting-started) to learn how to add Advanced Tables to your resources, relation managers, pages, and/or table widgets.

### Setting up Advanced Tables in Filament Table Builder

> If using Filament Panels, please refer to the [Filament Panels setup instructions](#setting-up-advanced-tables-in-filament-panels-including-relation-managers-and-table-widgets).

> Important: Beyond the [normal requirements](#requirements), using Advanced Tables with Filament Table Builder requires you have some type of user authentication system such as [Laravel Breeze](https://laravel.com/docs/10.x/starter-kits#laravel-breeze) since each view belongs to the currently authenticated user.

1. Publish the config files

    While optional, it is recommended you publish the config file to be able to fully customize Advanced Table. However, If you are using a User class other than Laravel's default `User::class` or a user's table other than Laravel's default `users` you should publish the config file and update these configurations **before** migrating.

    ```bash
    php artisan vendor:publish --tag="advanced-tables-config"
    ```

2. Publish the language files

    Optionally, publish the language files:

    ```bash
    php artisan vendor:publish --tag="advanced-tables-translations"
    ```

3. Publish and run the migrations

    ```bash
    php artisan vendor:publish --tag="advanced-tables-migrations"
    php artisan migrate
    ```

4. Add the `HasViews` trait to your `User::class`
    
    ```php
    use Archilex\AdvancedTables\Concerns\HasViews;

    class User
    {
        use HasViews;
    }
    ```

5. Integrate Advanced Tables's custom css file

    Add the following line to the top of your `app.css` file:
    
    ```css
    @import '../../vendor/archilex/filament-filter-sets/resources/dist/advanced-tables.css';
    ```

6. Compile

    Next, compile your theme:

    ```bash 
    npm run build
    ```

    Finally, run the Filament upgrade command:

    ```bash
    php artisan filament:upgrade
    ```

7. Setting up tenancy

    If you are installing Advanced Tables into a multi-tenancy application, please refer to the separate instructions to [set up multi-tenancy](#multi-tenancy).

After you've successfully installed Advanced Tables, you may review the [Getting Started guide](#filament-table-builder) to learn how to add Advanced Tables to your tables.

### Deploying

When deploying, it is not advised to store your `auth.json`` file inside your project's version control repository. To store your credentials on your deployment server you may create a [Composer auth.json file](https://getcomposer.org/doc/articles/http-basic-authentication.md) in your project directory using the following command: 

```bash
composer config http-basic.filament-filter-sets.composer.sh your_account_email your_license_key_including_your_fingerprint_domain
```

> Important: Don't forget to append a colon (:) and your fingerprint domain to your password.

You can see your credentials in your [Anystack account](https://account.anystack.sh/transactions): `Anystack > Transactions > View details` next to Filament Filter Sets. 

> Tip: Make sure the `auth.json` file is in `.gitignore` to avoid leaking credentials into your git history.

If you are using Laravel Forge, you don't need to create the `auth.json` file manually. Instead, you can set the credentials on the `Composer Package Authentication` screen of your server. 

#### Fixing deployment errors

1. The most common mistake when deploying, is not adding the colon (:) followed by the domain you registered. `license_key:domain`. Please review the instructions above.

2. If you have set up everything correctly and are getting the error: `../advanced-tables-for-filament-3.7.29.zip' URL required authentication (HTTP 401). You must be using the interactive console to authenticate` error, you may need to ssh into your server and clear your composer global cache with `composer clear-cache`

## Upgrading to v3

### New features

Advanced Tables v3 is the biggest release since it's initial launch and contains numerous improvements over v1 and v2. Here are some of the exciting new features:

- The new [View Manager](#view-manager-new) allows users to edit, manage, and sort their views right on the table
- A new [Quick Save](#quick-save-new) button means saving views is just one click away
- [User Views](#user-views) can now include grouping and column order
- SlideOver, modal, and dropdown options
- [Preset Views](#preset-views) (formerly developer-created filter sets) can now include filters, grouping, and columns
- Preset Views can now be [favorited, hidden, and sorted](#disabling-preset-view-management-new) by the user
- Columns can now be reordered with the enhanced [toggled column manager](#reordering-columns)
- A new [approval system](#approving-public-and-global-favorite-user-views-new) allows admins to approve or reject public and global favorites
- Support for Multi-tenancy
- Two new [themes](#themes) (Github and Filament)
- Easily add colors to the color picker using Filament's `Color::class`
- More than 60 configuration options to completely customize Advanced Tables to your needs

### Upgrading

Advanced Tables is almost a complete rewrite of previous releases and thus requires numerous changes to completely upgrade. I've tried to document every required change, but if you have issues or if I have missed a step, please reach out to me at advancedtables@gmail.com.

#### Before you begin

Before you begin, be sure to follow the setup instructions for [Filament panels](#setting-up-advanced-tables-in-filament-panels-including-relation-managers-and-table-widgets) or [Table Builder](#setting-up-advanced-tables-in-filament-table-builder).

#### High-impact changes

##### Migrations

Due to the namespace changes, you may need to update your old migrations to use the new namespacing. If you are updating a local project and you have *not yet* deployed to production, you can just delete the old migrations and publish the new ones. 

However, if you have *already* deployed to your production server, you will most likely need to update your *local* migrations so you don't run into errors when trying to `migrate:fresh`:

In your local `yyyy_mm_dd_xxxxxx_create_filament_filter_sets_table` and your `yyyy_mm_dd_xxxxxx_create_filament_filter_set_user_table` migrations, change:

`use Archilex\FilamentFilterSets\Support\Config;` to `use Archilex\AdvancedTables\Support\Config;`

If you wish you can also update the deprecated methods in both migration files:

Change `$userClass = Config::getUserModelName();` to  `$userClass = Config::getUser();`

> Important: If you have already deployed to your production server, do **NOT** delete and republish these two migration files. Doing this will create new migration files and when deploying to production you will encounter errors as the database tables have already been created.

##### Filter Set Filter 

The previous `FilterSetFilter` that lived in the `filters` dropdown has replaced by the [Quick Save](#quick-save-new) button to save new views and the [View Manager](#view-manager-new) to select and manage them. This means you should remove the `FilterSetFilter` and its imported class `use Archilex\FilamentFilterSets\Filters\FilterSetFilter` from each of your tables.

It will also be important for you to educate your end-users accordingly.

##### HasFavorites 

The entry point to using Advanced Tables is now the `AdvancedTables` trait which replaces the previous `HasFavorites` trait. Remove the previous trait and class import and add the new one. 

```php
// use Archilex\FilamentFilterSets\Concerns\HasFavorites;
use Archilex\AdvancedTables\AdvancedTables;

class ListUsers extends ListRecords
{
    // use HasFavorites;
    use AdvancedTables;
```

> Important: Previously, you would only need to use the `HasFavorites` trait if you wanted to use the Favorites Bar on a table. As of v3, the `AdvancedTables` trait is the main entry point for the plugin. This means that anywhere you were using `FilterSetFilter` without the respective `HasFavorite` trait you will now need to add the `AdvancedTables` trait to the appropriate class, usually `List*` or `Manage*`.

##### Heroicons

Filament v3 now uses Heroicons v2. If you are upgrading from Filter Sets v1 *and* you and/or your users were using icons with their views, these icons will need to be updated. Advanced Tables includes a helper service that you may enable to automatically convert icons stored in the database on the fly. You can enable this helper by adding the `convertIcons()` method to the `AdvancedTablesPlugin` object inside your `PanelProvider`: 

```php
public function panel(Panel $panel): Panel
{
    return $panel
        ->plugins([
            AdvancedTablesPlugin::make()
                ->convertIcons()
        ])
```

> The helper service exists to get you up and running as quickly as possible. However, when convenient, it's recommended you implement your own script to update the icons directly in your database and then disable this helper.

#### Developer-created Filter Sets are now Preset Views

Developer-created Filter Sets are now Preset Views and should be updated accordingly:

1. The `getFilterSets()` should be renamed to `getPresetViews()`.
2. The `FilterSet` object should be renamed to `PresetView` and it's class imported.
3. The name of your Preset View should become the `array key`.
4. `toggledColumns` has been renamed to `defaultColumns`.
5. Any v1 Heroicons should be [updated to v2](https://github.com/tailwindlabs/heroicons/releases/tag/v2.0.0). 
6. Any Preset View you wish to display in the Favorites Bar should use the `favorite()` method.

Before
```php
use Archilex\FilamentFilterSets\Components\FilterSet;

class ListUsers extends ListRecords
{
    public function getFilterSets(): array
    {
        return [
            FilterSet::make('Delivered this month')
                ->query(fn ($query) => $query->where('status', 'delivered'))
                ->toggledColumns(['id', 'name'])
        ];
    }
}
```

After
```php
use Archilex\AdvancedTables\Components\PresetView;

class ListUsers extends ListRecords
{
    public function getPresetViews(): array
    {
        return [
            'delivered_this_month' => PresetView::make()
                ->label('Delivered')
                ->query(fn ($query) => $query->where('status', 'delivered'))
                ->defaultColumns(['id', 'name'])
                ->favorite()
        ];
    }
}
```

> Important: Be sure that any column included in `defaultColumns` is present in on the `columns` method of your table.

##### Filter Set Resource is now User Views Resource

Since users can now edit, delete, and sort their views in the View Manager, the User Views Resource (formerly Filter Set Resource) has been updated to be a tool *exclusively* for admin users as it now lists *every* user's views. You will most likely want to [limit access](#authorization) to this resource to admins.

#### Medium-impact changes

##### Combining Preset Views into a dropdown

Since the new View Manager displays *all* views, including Preset Views, combining Developer-created Filter Sets into a dropdown using the `showDeveloperFilterSetsAsDropdown` method is now redundant. However, if needed, you may enable this functionality using the `presetViewLegacyDropdown()` method:

```php
AdvancedTablesPlugin::make()
    ->presetViewLegacyDropdown()
```

##### Config file customizations

All of the customizations that were previously managed in the `filament-filter-sets.php` config file are now managed on the `AdvancedTablesPlugin` object inside your `PanelProvider`. For easy reference, here are the previous customization options linked to their respective sections in the documentation:

- [models.user](#userclass)
- [models.filter_set](#configuring-the-user-view-model)
- [models.filter_set_user](#configuring-the-managed-user-view-class)
- [user_table_name_column](#configuring-the-user-name-columns)
- [filter_set_resource.enabled](#disabling-the-user-views-resource)
- [filter_set_resource.load_all_users](#disabling-loading-all-users-in-the-user-select-filter)
- [favorites.view](#themes-1)
- [favorites.all_icon](#default-view-icon)
- [favorites.icon_position](#icon-position)
- [favorites.size](#size)
- [developer_filter_sets.can_create_using_developer_filter_sets](#disable-user-view-creation)
- [developer_filter_sets.display_divider_in_favorites](#divider)
- [developer_filter_sets.lock_icon](#display-a-lock-icon)
- [developer_filter_sets.display_helper_text](#display-helper-text-in-the-save-view-slideover-or-modal)
- [colors](#configuring-the-color-picker-colors-new)
- [forms.display_helper_text](#showinghiding-helper-text)
- [forms.display_icon_select](#disabling-the-icon-picker)
- [forms.display_color_picker](#disabling-the-color-picker)

> Note: If you are using the standalone Table Builder the configurations are handled in the new `advanced-tables.php` config file.

##### Language files

The language files have been completely reworked to match the new terminology. Since the language files have been renamed, there isn't a risk of missing translations, but if you had previously published and modified your language files, you will need to [publish](#setting-up-advanced-tables-in-filament-panels-including-relation-managers-and-table-widgets) and update the new ones. 

#### What's next

Now that you've successfully upgraded, be sure to take a look at all the [new features](#new-features) for additional options.

## Getting started

### Adding Advanced Tables to your table

To use Advanced Tables you will need to add the `AdvancedTables` trait to the appropriate class depending on whether you intend to use it on a [Resource Table](#resource-tables), [Simple Resource Table](#simple-modal-resource-tables), [Table Widget](#table-widgets), or [Panel Page](#panel-pages).

> Important: For standalone Table Builder users, please refer to the documentation for [using Advanced Tables with Table Builder](#filament-table-builder).

#### Resource tables

To add Advanced Tables to a normal [Resource](https://filamentphp.com/docs/3.x/panels/resources/getting-started) table, add the `AdvancedTables` trait to the [List page](https://filamentphp.com/docs/3.x/panels/resources/listing-records) of your `Resource`:

```php
use Archilex\AdvancedTables;

class ListProducts extends ListRecords
{
    use AdvancedTables;
```

#### Simple (modal) resource tables

To add Advanced Tables to a [Simple (modal) resource](https://filamentphp.com/docs/3.x/panels/resources/getting-started#simple-modal-resources) table, add the `AdvancedTables` trait to the `Manage page`:

```php
use Archilex\AdvancedTables;

class ManagesCustomers extends ListRecords
{
    use AdvancedTables;
```

#### Table Widgets

To add Advanced Tables to a Table Widget, add the `AdvancedTables` trait to the [Table widget](https://filamentphp.com/docs/3.x/panels/dashboard#table-widgets):

```php
use Archilex\AdvancedTables;

class LatestOrders extends BaseWidget
{
    use AdvancedTables;
```

#### Panel Pages

To add Advanced Tables to a [Panel Page](https://filamentphp.com/docs/3.x/panels/pages), you need to add the `AdvancedTables` trait to your component. However, as Advanced Tables overrides multiple methods in Filament's `InteractsWithTables` trait, adding the `AdvancedTables` trait to the table will cause a conflict. 

For convenience, Advanced Tables includes a `PanelPage` class which you can use to quickly get up and running:

```php
use Archilex\AdvancedTables\AdvancedTables;
use Archilex\AdvancedTables\Livewire\PanelPage;

class CustomPage extends PanelPage
{
    use AdvancedTables;

    ...
```

Of course, there are multiple ways to prevent the trait conflict. The important part is to ensure that the `AdvancedTables` trait is used on a class that extends another class which contains Filament's `InteractsWithTables` trait.

#### Adding the view component to your blade file

You also need to add the Favorites Bar component to your panel page's blade file:

```html
<div class="space-y-6">
    
    <x-advanced-tables::favorites-bar />

    {{ $this->table }}
</div>
```

The Favorites Bar expects a space of `24px` to properly display it's links. This can easily be achieved with Tailwind's `space-y-6` class as shown above.

### Core Concept: User Views vs Preset Views

Advanced Tables supports both *User Views* and *Preset Views*. Understanding the difference is important to choosing if one or both is appropriate for your application.

**User Views** are created by your end-users using your application's UI. An end-user chooses the appropriate filters, toggled columns, column order, column sort, table grouping, etc. to build the view they need. Then they use Advanced Tables to save that view so they have easy access to it in the future. Since each user has different needs, this allows for infinite customization within your application. (And less work for developers!)

**Preset Views** are views that you the developer write in code and are then available to all your users, (or the users you authorize). Preset Views exposes a `query()` api which allows you to modify the underlying eloquent query. This means you can "filter" a table's data without needing to have that filter on your table. 

However, while being able to modify the underlying eloquent query is powerful, and in some cases might be the only way to filter a table, Advanced Tables v3 introduces a new `filters()` api which allows you to apply values to your existing table filters. This, in turn, offers a better UX for your end-users as they will then see filter indicators in the table and will better understand how a Preset View is modifying the data. 

Whether used independently or together, User Views and Preset Views give your end-users quick access to the data they need.

## User Views

User Views are views created by your end-users using your application's UI. An end-user chooses the appropriate filters, toggled columns, column order, column sort, table grouping, etc. to build the view they need. Then they use Advanced Tables to save that view so they have easy access to it in the future. Since each user has different needs, this allows for infinite customization within your application. (And less work for developers!)

### Saving the current table configuration into a User View

To save a User View:
1. On your table, apply any combination of filters, toggled columns, sort order, grouping, etc.
2. After customizing your table, click the `+` in the top right corner of the table.
3. Choose a name, icon, and color for the view. 
4. Choose if you want the view to be added to your favorite views, made public for other users, or be a global favorite.
5. Save the view

When creating a user view the following configurations will be saved:
- current filters, 
- table search query, 
- column search queries (if enabled)
- column sort order
- toggled columns
- column order
- grouping

### Editing a User View's name, icon, color or visibility

The View Manager allows a user to edit a User View's name, icon, color, and/or visibility. 

1. Open the View Manager.
2. Next to the view you wish to edit, click the action button, and choose `Edit view`.
3. Update the name, icon, color, and/or visibility
4. Click `Save changes`

To change the configuration of filters, columns, grouping, etc. see [Editing a User View's table configuration](#editing-a-user-views-table-configuration)

### Editing a User View's table configuration

To update a User View's table configuration of filters, columns, grouping, etc. you can use the `Replace view` action:

1. Set the table up with the desired configuration.
2. Open the View Manager.
3. Next to the view you want to update, click the action button, and choose `Replace view`.

Replacing a view will overwrite the existing view with the current table's configuration.

If you would like to just update the name, icon, color, and/or visibility of a view, see [Editing a User View's name, icon, color or visibility](#editing-a-user-views-name-icon-color-or-visibility)

### Deleting a User View

User views can be deleted in the View Manager using the [view's action](#action-button) button.

### Sorting a view

User views can be sorted in the View Manager. Refer to the section [Sorting views](#sorting-views) of the View Manager for additional details.

### User View configurations

Advanced Tables offers multiple ways to customize User Views. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`: 

```php
public function panel(Panel $panel): Panel
{
    return $panel
        ->plugins([
            AdvancedTablesPlugin::make()
                ->userViewsEnabled(false)
        ])
```

#### Disable User Views (New)

User Views are enabled by default. However, if you are not going to use User Views, you should disable them to prevent unnecessary database queries:

```php
AdvancedTablesPlugin::make()
    ->userViewsEnabled(false)
```

#### Configuring the User View model

The `UserView` model is responsable for storing all the configuration settings for each User View. If you need to extend this class, you may pass your custom class to `userView()`:

```php
AdvancedTablesPlugin::make()
    ->userView(MyCustomUserView::class)
```

#### Configuring the Managed User View class

The `ManagedUserView` model is responsable for managing the visibility and sort order between a `User` and a `UserView`. If you need to extend this class, you may pass your custom class to `managedUserView()`:

```php
AdvancedTablesPlugin::make()
    ->managedUserView(myCustomManagedUserView::class)
```

#### Disabling the icon picker

You may disable the icon picker in the Save View/Edit View slideOver by passing `false` to the `quickSaveIconSelect()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveIconSelect(false)
```

You may also use [policies](#authorization) to configure who can use the icon picker.

#### Excluding solid or outline icons

By default the icon picker loads all of heroicons solid and outline icons. You may exclude either solid or outline icons by passing false to either the `quickSaveIncludeOutlineIcons()` or `quickSaveIncludeSolidIcons()` methods:

```php
AdvancedTablesPlugin::make()
    ->quickSaveIncludeSolidIcons(false)
```

> Important: Since icons are cached, after updating you will need to clear your cache to see the change with `php artisan cache:clear`.

#### Configuring the color picker colors (New)

By default, the color picker will include Filament's [default colors](https://filamentphp.com/docs/3.x/support/colors#customizing-the-default-colors), `primary`, `success`, `info`, `warning`, `danger`, `gray`. To configure the available colors, pass an array of colors to `->quickSaveColors()`:

```php
AdvancedTablesPlugin::make()
    ->quickSaveColors([
        'primary',
        'warning',
        'gray',
    ])
```

You may also include any [extra colors you have previously registered in Filament](https://filamentphp.com/docs/3.x/support/colors#registering-extra-colors):

```php
AdvancedTablesPlugin::make()
    ->quickSaveColors([
        'primary',
        'success',
        'indigo',
        'pink',
        'zinc',
    ])
```

#### Disabling the color picker

You may disable the color picker in the Save View/Edit View slideOver by passing `false` to the `->quickSaveColorPicker()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveColorPicker(false)
```

You may also use [policies](#authorization) to configure who can use the color picker.

#### Making a User View favorite

By default, when creating/editing a view, users can favorite their views by toggling on `Add to favorites`. Favorite views are added to the Favorites Bar and appear above the table. Refer to the [Favorites Bar](#favorites-bar) section for additional details.

#### Disabling making a User View favorite

You may disable the ability to make a User View favorite by passing `false` to the `->quickSaveMakeFavorite()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveMakeFavorite(false)
```

You may also use [policies](#authorization) to configure who can make views favorite.

#### Making a User View public

By default, when creating/editing views, users can share their views with other users by toggling on `make public`. Public views will appear in other user's View Manager where they can then be added to their favorites if they wish.

Advanced Tables also has an [approval system](#approving-public-and-global-favorite-user-views-new) so admins can approve public views before they are visible to other users.

#### Disabling making a User View public

You may disable the ability to make a User View public using the `->quickSaveMakePublic()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveMakePublic(false)
```

You may also use [policies](#authorization) to configure who can make views public.

#### Enabling making a User View a global favorite

Making a User View a global favorite automatically adds it to every user's Favorites Bar. As this is an action usually reserved for admin users, this functionality is turned off by default. You may enable the ability to make a User View a global public using the `->quickSaveMakeGlobalFavorite()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveMakeGlobalFavorite()
```

After enabling, you may use [policies](#authorization) to further configure who can make views global favorites.

Advanced Tables also has an [approval system](#approving-public-and-global-favorite-user-views-new) so admins can approve global favorite views before they are visible to other users.

#### Disabling management of global favorite views (New)

As previously mentioned, when an admin or user creates a global favorite view, that view is added to all user's Favorites Bar. By default, these global views can then be managed (ie. sort and favorite/un-favorite) independently by each user. If you need to disable management of global User View you may do so by passing `false` to the `->globalUserViewsManageable()` method:

```php
AdvancedTablesPlugin::make()
    ->globalUserViewsManageable(false)
```

By disabling `globalUserViewsManageable`, global favorites will be not be able to be sorted nor removed from a user's Favorites Bar.

#### Configuring new global user view's sort position (New)

When global favorite management is disabled, all global favorites are added *before* any User Views that a user has favorited. However, when global view management is enabled, a user is then free to reorder them, placing global views before, after, or in between their own user-favorited views. Now, when a *new* global view is created by an admin, a decision needs to be made as to whether this new global view should be placed `before` or `after` the user's previously ordered favorite views. By default new global views are positioned `before` a user's favorited views, however this can be configured using the `newGlobalUserViewSortPosition()` method:

```php
AdvancedTablesPlugin::make()
    ->newGlobalUserViewSortPosition('after')
```

#### Showing/hiding helper text

When creating/editing User Views you may show/hide helper text to help guide your end-users during the process. By default, helper text is only displayed for the Favorite, Public, and Global Favorite toggles.

```php
AdvancedTablesPlugin::make()
    ->quickSaveNameHelperText(false)
    ->quickSaveFiltersHelperText(false)
    ->quickSavePublicHelperText(false)
    ->quickSaveFavoriteHelperText(false)
    ->quickSaveGlobalFavoriteHelperText(false)
```

You may configure the wording of each helper text by modifying the [language file](#language-files).

#### Approving public and global favorite User Views (New)

Advanced Tables includes a simple approval mechanism to allow admins to approve/reject public and global favorites before they are made available to other users.

Advanced Tables uses [Filament's enum](https://filamentphp.com/docs/3.x/support/enums) to define the  `Status` constants:

```php
enum Status: string implements HasLabel, HasColor
{
    case Approved = 'approved';
    case Pending = 'pending';
    case Rejected = 'rejected';
```

To use the approval system, first, set the User View's `initialStatus()` to either `Status::Approved`, `Status::Pending`, or `Status::Rejected`. By default, each User View has an initial status of `Status::Pending`:

```php
AdvancedTablesPlugin::make()
    ->initialStatus(Archilex\AdvancedTables\Enums\Status::Rejected)
```

Then, set the `minimumStatusForDisplay()` to either `Status::Approved`, `Status::Pending`, or `Status::Rejected`. By default, the minimal status is `Status::Pending`:

```php
AdvancedTablesPlugin::make()
    ->minimumStatusForDisplay(Archilex\AdvancedTables\Enums\Status::Approved)
```

When a User View's status is the equal or greater than the `minimumStatusForDisplay()`, it will be displayed to other users. 

Advanced Tables default setting of `Pending` for both `Status` and `minimumStatusForDisplay` means that all public and global User Views will automatically be displayed to other users, effectively bypassing the approval system. Changes only need to be made if you would like to enable the approval system.

To update the status of a User View, admin should use the [User Views Resource](#user-views-resource).

Of course, Laravel's [Observers](https://laravel.com/docs/10.x/eloquent#observers) can be implemented on the `UserView` model to further expand the approval system with database or email notifications.

#### Persisting the active User View to Session

Persisting the active User View to the session allows a user to navigate away from the table and then return to the table with the same view selected. You may enable this by using the `->persistActiveViewInSession()` method:

```php
AdvancedTablesPlugin::make()
    ->persistActiveViewInSession()
```

## Preset Views

In addition to [User Views](#user-views), developers can also programmatically create Preset Views in code that can be deployed to all users. Preset Views exposes a `query()` api which allows you to modify the underlying eloquent query. This means you can "filter" a table's data without needing to have that filter on your table. 

However, while being able to modify the underlying eloquent query is powerful, and in some cases might be the only way to filter a table, Advanced Tables v3 introduces a new [`defaultFilters()`](#applying-filters-new) api which allows you to apply values to your table filters. This, in turn, offers a better UX for your end-users as they will then see filter indicators in the table and will better understand how a Preset View is modifying the data. 

For more information on the difference between User Views and Preset Views please refer to [Core Concept: User Views vs Preset Views](#core-concept-user-views-vs-preset-views)

### Filament Filter Tabs
Filament v3 introduced `Filter Tabs` which also allows developers to programmatically filter their data in tabs. While similar, Advanced Tables' Preset Views offers multiple additional features:

- Allow users to hide, favorite, and/or reorder Preset Views (New)
- Combine with User Views for one consistent UI
- Relation manager support
- Table builder support
- Multiple themes
- Include filters (New)
- Include toggled columns
- Include sorting column and direction
- Include reordered columns (New)
- Persist the active Preset View to the session
- Color options
- Visibility options

### Creating a Preset View

To create a Preset View, add the `getPresetView()` method to your `List*`, `Manage*`, or table widget class.

```php
use Archilex\AdvancedTables\Components\PresetView;
use Archilex\AdvancedTables\AdvancedTables;
 
class ListOrders extends ListRecords
{
    use AdvancedTables;
 
    public function getPresetViews(): array
    {
        return [
            'processing' => PresetView::make()
                ->modifyQueryUsing(fn ($query) => $query->where('status', 'processing')),
            'delivered' => PresetView::make()
                ->modifyQueryUsing(fn ($query) => $query->where('status', 'delivered')),
        ];
    }
}
```

The Preset View `modifyQueryUsing()` method modifies your original eloquent query by applying the scopes and conditions you configure.

### Customizing the Preset View label

By default the array keys will be used as the labels for each Preset View. This may be configured by passing a label into the `make()` method:

```php
'processing' => PresetView::make('Processing orders')
    ->modifyQueryUsing(fn ($query) => $query->where('status', 'processing'))
    ->favorite(),
```

If you prefer, you may also use the `label()` method:

```php
'processing' => PresetView::make()
    ->label('Processing orders')
    ->modifyQueryUsing(fn ($query) => $query->where('status', 'processing'))
    ->favorite(),
```

### Adding a Preset View to the Favorites Bar

By default, Preset Views are added to the View Manager in the Preset View section. To add a Preset View to the Favorites Bar use the `favorite()` method:

```php
'processing' => PresetView::make()
    ->modifyQueryUsing(fn ($query) => $query->where('status', 'processing'))
    ->favorite(),
```

Due to the [fundamental difference](#core-concept-user-views-vs-preset-views) between User Views and Preset Views, favorited Preset Views always appear *before* a User Views in the Favorites Bar. 

### Adding an icon

Similar to User Views, Preset Views may have icons:

```php
'processing' => PresetView::make()
    ->modifyQueryUsing(fn ($query) => $query->where('status', 'processing'))
    ->icon('heroicon-o-refresh'),
```

By default the icon will be displayed before the name. This [can be configured](#icon-position) in the Favorites Bar settings.

### Display the Preset View with a color

Similar to User Views, Preset Views may be displayed in a color. 

```php
'processing' => PresetView::make()
    ->modifyQueryUsing(fn ($query) => $query->where('status', 'processing'))
    ->color('warning'),
```

You may choose any of Filament's [default colors](https://filamentphp.com/docs/3.x/support/colors#customizing-the-default-colors), `primary`, `success`, `info`, `warning`, `danger`, `gray`. 

You may also include any [extra colors you have previously registered in Filament](https://filamentphp.com/docs/3.x/support/colors#registering-extra-colors):

### Adding a badge (New)

Preset Views can display a badge after the label by passing a string into the `badge()` method:

```php
'processing' => PresetView::make()
    ->badge(Order::query()->where('status', 'processing')->count())
```

### Changing the badge color (New)

The color of a badge may be changed using the `badgeColor()` method:

```php
'processing' => PresetView::make()
    ->badge(Order::query()->where('status', 'processing')->count())
    ->badgeColor('warning')
```

> Tip: If you want to display multiple badges, you should generate one query separately and then use [Laravel collections](https://laravel.com/docs/10.x/collections#main-content) to filter and count them.

### Adding a tooltip (New)

Preset Views can display a tooltip when hovered over in the Favorites Bar by passing a string into the `tooltip()` method.:

```php
'lowStock' => PresetView::make()
    ->modifyQueryUsing(Product::query()->where('price', '>', 1000)->where('qty', '<', 5))
    ->tooltip('High price products with low stock')
```

### Showing or hiding

You may conditionally show or hide Preset Views for certain users using either the `visible()` or `hidden()` methods, passing a closure:

```php
'processing' => PresetView::make()
    ->visible(fn (): bool => auth()->isAdmin())
```

You can also use a [Laravel policy](https://laravel.com/docs/10.x/authorization#creating-policies) to manage visibility:

```php
'processing' => PresetView::make()
    ->visible(fn (Order $record): bool => auth()->user()->can('viewProcessing', $record)),
```

And then in `OrderPolicy`:

```php
public function viewProcessing(User $user)
{
    return $user->isAdmin();
}
```

> Tip: If your policy is not working, be sure to register it in `AuthServiceProvider` as sometimes Laravel does not successfully auto-register policies.

### Applying filters (New)

You can apply values to your [table filters](https://filamentphp.com/docs/3.x/tables/filters) from your Preset Views with the `defaultFilters()` method:

```php
'new_this_quarter' => PresetView::make()
    ->defaultFilters([
        'status' => [
            'value' => 'new',
        ],
        'created_at' => [
            'range' => 'this_quarter',
        ],
    ])
```

Using the `defaultFilters()` api gives your users a better understanding of how a Preset View is filtering the data by turning on Filament's filter indicators.

> Tip: The easiest way to know how to properly form your filter array is to apply the desired filter to your table and then `dd($this->tableFilters)` at the top of the `getPresetViews()` method.

### Applying filters with Filter Builder (New)

If you are using [Advanced Filter Builder](#advanced-filter-builder-new), you should use the following syntax to define your default filters:

```php
'follow_up' => PresetView::make()
    ->defaultFilters([
        'advanced_filter_builder' => [
            [ // filter group 1
                'status' => [
                    'value' => 'new'
                ],
                'created_at' => [
                    'range' => 'this_month',
                ],
            ],
            [ // filter group 2 (ie: "or")
                'status' => [
                    'value' => 'cancelled'
                ],
                'created_at' => [
                    'range' => 'last_month',
                ],
            ],
        ],
    ])
```

If the example above, this will create the following query scope: `new orders made this month` OR `cancelled orders made last month`.

> Tip: The easiest way to know how to properly form your filter array is to apply the desired filter to your table and then `dd($this->tableFilters)` at the top of the `getPresetViews()` method.

If you are using the builder's [Column Filters](#enabling-column-filters), then you will need to add the applicable values. For example:

```php
'this_quarter' => PresetView::make()
    ->defaultFilters([
        'advanced_filter_builder' => [
            [ // filter group 1
                'created_at' => [
                    'column' => 'created_at', 
                    'operator' => 'in_the_last',
                    'value' => 1,
                    'unit' => 'quarters',
                ],
            ],
        ],
    ])
```

> Tip: Many of the column filters have multiple `keys` such as `date_start`, `date_end`, etc. You only need to add the values that you are setting for the filter.

### Applying default grouping (New)

You can apply one of your table [groupings](https://filamentphp.com/docs/3.x/tables/grouping#overview) to your Preset View with the `defaultGrouping()` method:

```php
'new_this_quarter' => PresetView::make()
    ->defaultGrouping('created_at', 'desc')
```

### Toggling and reordering columns (New)

Preset Views can toggle columns, and, if [Reorderable Columns](#reorderable-columns-new) are enabled, can reorder them as well using the `defaultColumns()` method: 

```php
'processing' => PresetView::make()
    ->defaultColumns(['id', 'status', 'customer.name', 'created_at'])
```

Columns will be saved in the following ways:

- If Reorderable Columns are enabled, Advanced Tables will sort the columns in the order they are included in the `defaultColumns()` array. 
- If a column is not included in the array and is `toggleable()`, it will be hidden. 
- If a column is not included in the array and is not `toggleable()`, it will be added to the end of the table.

### Setting a default table sort

If a column is [sortable](https://filamentphp.com/docs/3.x/tables/getting-started#making-columns-sortable-and-searchable), you may choose it as the default sort column for your table using the `defaultSort()` method:

```php
'processing' => PresetView::make()
    ->defaultSort('total_price')
```

By default, sorting is ascending, but you may choose descending as well `->defaultSort('total_price', 'desc')`. 

> Tip: While it is possible to add `orderBy()` to your query to sort your table, using `defaultSort()` is recommended as it will correctly show the sorting indicator on the table column.

### Setting a default table multi-sort (New)

If [Multi-Sort](#multi-sort-beta) is enabled, you may multi-sort your preset views through the same `defaultSort()` method. Just pass an array of columns and their sort direction to `defaultSort()`:

```php
'processing' => PresetView::make()
    ->defaultSort([
        'is_visible' => 'desc',
        'price' => 'asc'
    ])
```

### Loading a default Preset View

You may choose one of your Preset Views as the default view when loading the page by using the `default()` method:

```php
'processing' => PresetView::make()
    ->default()
```

`default()` can take a callback which can allow you to dynamically choose which Preset View is the default based on the conditions you choose. The first Preset View that returns `true` will be the view that is loaded by default. 


### Preserving user selected filters, toggled columns, sort column, and sort direction

By default, when an end-users clicks a Preset View, the filters, toggled columns, sort column, and sort direction that a user has already applied to a table will be removed in favor of the Preset View's configuration. This is usually the desired behavior as Preset Views are meant to be customized views into data. However in some instances, you may wish to preserve the user's selected filters, columns, etc. To do this you may use `preserveAll()`. 

```php
'processing' => PresetView::make()
    ->preserveAll()
```

If you need more fine-grained control you may use the individual methods:

```php
'processing' => PresetView::make()
    ->preserveFilters()
    ->preserveToggledColumns()
    ->preserveSortColumn()
    ->preserveSortDirection()
```

> Note: By preserving a user's selection you are in turn removing the option for a Preset View to always take a user to that view's predefined configuration as that view is now affected by the user.

### Preset Views configurations

Advanced Tables offers multiple ways to customize Preset Views. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`: 

```php
public function panel(Panel $panel): Panel
{
    return $panel
        ->plugins([
            AdvancedTablesPlugin::make()
                ->createUsingPresetView(false)
        ])
```

#### Configuring the Managed Preset View class (New)

The `ManagedPresetView` class is responsable for storing the visibility and sorting configurations between a `User` and a `PresetView` If you need to extend this class, you may pass your custom class to `managedPresetView()`:

```php
AdvancedTablesPlugin::make()
    ->managedPresetView(myCustomManagedPresetView::class)
```

#### Disabling Preset View management (New)

By default, Preset Views will be sorted in the order they are added to the `getPresetViews()` array. Similarly, any Preset View that has the `favorite()` method will be displayed by default in the end-user's Favorites Bar, and any Preset View without `favorite()` will be displayed in the View Manager.

Advanced Tables v3 now allows Preset Views to be managed by the end-user. Users can sort Preset Views as well as add/remove them from the Favorites Bar. 

If you need to disable Preset View management you may do so by passing `false` to the `->globalUserViewsManageable()` method:

```php
AdvancedTablesPlugin::make()
    ->presetViewsManageable(false)
```

By disabling `presetViewsManageable`, Preset Views will be not be able to be sorted nor added/removed from a user's Favorites Bar.

#### Configuring new Preset Views sort position (New)

When Preset View management is enabled, a user is free to reorder, add or remove them from their Favorites Bar. Now, when a *new* Preset View is added in code and then deployed to the user, a decision needs to be made as to whether this new Preset View should be placed `before` or `after` the user's previously ordered Preset Views. By default new Preset Views are positioned `before` a user's current Preset View ordering, however this can be configured using the `newPresetViewSortPosition()` method:

```php
AdvancedTablesPlugin::make()
    ->newPresetViewSortPosition('after')
```

#### Persisting the active Preset View to Session

Persisting the active Preset View to the session allows a user to navigate away from the table and then return to the table with the same view selected. You may enable this by using the `->persistActiveViewInSession()` method in your `Panel Provider`:

```php
AdvancedTablesPlugin::make()
    ->persistActiveViewInSession()
```

#### Distinguishing between Preset Views and Users Views

Enabling both Preset Views and User Views has the potential of causing confusion with end-users if they create a User View *on top of* a Preset View. This is because a Preset View can "filter" the table using the `query()` method which doesn't correspond to any filter on the table. This means that when a user builds a User View using a Preset View as its base, there's no way for the user to "turn off" the filter scope. 

While Advanced Tables has multiple options you can use to mitigate these potential issues, the easiest way around this issue is to *not* use the `query()` method and instead use the `defaultFilters()` method. This way, even when a user creates a User View based on a Preset View, they are in full control of data. 

However, if you still need, or prefer, to use the `query()` method to filter your data, you can use these options to help avoid confusion. These configurations should be applied to the `AdvancedTablesPlugin` in your `Panel Provider`.

##### Disable User View creation

You can disable the creation of User Views all together when a Preset View is selected. If disabled, when a user clicks the Quick Save Button, a Filament notification will be displayed explaining that this action is not possible. The text of the notification can be configured in the [language file](#language-files).

```php
AdvancedTablesPlugin::make()
    ->createUsingPresetView(false)
```

##### Display a divider line

You can optionally display a divider line between Preset Views and User Views to help visually distinguish between the two. 

```php
AdvancedTablesPlugin::make()
    ->favoritesBarDivider()
```

##### Display a lock icon

You can optionally display an icon next to a Preset View to help visually distinguish between the two. 

```php
AdvancedTablesPlugin::make()
    ->presetViewLockIcon()
```

By default `heroicon-o-lock-closed` will be used, however you may pass any heroicon icon to the method:

```php
AdvancedTablesPlugin::make()
    ->presetViewLockIcon('heroicon-o-star')
```

##### Display a query indicator in the Save View slideOver or modal (New)

Another option to help a user know how a Preset View is modifying the query is to use the `->indicator()` method on the Preset View:

```php
'honor_roll_students' => PresetView::make()
    ->modifyQueryUsing(fn ($query) => 
        $query->perfectAttendance()
            ->perfectGrades()
            ->withoutBehaviorReports()
    )
    ->indicator('students with perfect attendance, grades, and behavior')
```

By adding a string of text to the `indicator()` method, a new badge with the selected text will be displayed in the View Summary when creating a new view. 

##### Display helper text in the Save View slideOver or modal

Finally, you can display helper text in the slideOver or modal that explains that the user has chosen a Preset View as the base for their User View and that the filtering applied in the Preset View set cannot be removed. This text can be configured in the [language file](#language-files).

```php
AdvancedTablesPlugin::make()
    ->quickSaveActivePresetViewHelperText()
```

#### Displaying the legacy dropdown

Version 1 of Advanced Tables (Filter Sets), introduced the ability to show Preset Views in a dropdown. This has been deprecated in favor of the [View Manager](#view-manager-new), however if you would still like to display it you may do so with the `presetViewLegacyDropdown()` method:

```php
AdvancedTablesPlugin::make()
    ->presetViewLegacyDropdown()
```

If you using the legacy dropdown, you may also want to [disable the view manager](#disable-view-manager).

## Favorites Bar

The Favorites Bar is home to all of a user's favorite views as well as Quick Save and View Manager. The Favorites Bar can be customized in a variety of ways to match the needs of your application.

### Favorites Bar configuration

Unless specified otherwise, these customizations can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`.

#### Themes

Advanced Tables includes six different themes for the Favorites Bar:

1. Links
2. Simple links
3. Branded tabs
4. Tabs
5. Github (New, default)
6. Filament (New)

You can change the theme with the 'favoritesBarTheme()` method:

```php
use Archilex\AdvancedTables\Enums\FavoritesBarTheme;

AdvancedTablesPlugin::make()
    ->favoritesBarTheme(FavoritesBarTheme::Filament)
```

You may also use the corresponding string instead:

```php
AdvancedTablesPlugin::make()
    ->favoritesBarTheme('filament')
```

> Note: Since `links-simple` only has color to visually distinguish between active and in-active states, it is recommended you [disable the ability to select a color](#disabling-the-color-picker) for their User Views since it becomes difficult to know which link is active.

#### Size

You may change the size of the Favorites Bar links to allow more links to be shown with the `favoritesBarSize()` method:

```php
use Filament\Support\Enums\ActionSize;

AdvancedTablesPlugin::make()
    ->favoritesBarSize(ActionSize::Small)
```

Available sizes are: `ActionSize::Small` and `ActionSize::Medium`.

#### Icon position

You may change the position of a view's icon in the Favorites Bar using the `favoritesBarIconPosition()` method:

```php
use Filament\Support\Enums\IconPosition;

AdvancedTablesPlugin::make()
    ->favoritesBarIconPosition(IconPosition::Before)
```

#### Disabling the Default View

By default, the Favorites Bar includes a Default View (previously named All). Clicking this will completely reset the table back to its default settings. You may disable the Default View using the `favoritesBarDefaultView()` method:

```php
AdvancedTablesPlugin::make()
    ->favoritesBarDefaultView(false)
```

You may also disable the Default View per resource by overriding the `hasDefaultView()` method in the class where you have added the AdvancedTables trait:

```php
public function hasDefaultView(): bool
{
    return false;
}
```

> Note: In prior versions this view was named `All`, however when clicking this view, it actually resets the table to it's ***default*** settings, which may or may not contain all the records. For this reason, it was renamed to `default` in version 3. However, you may change the name of the Default View in the [language file](#language-files).

> Tip: If you need an `All` button in addition/instead of a `Default` button, you can easily create a [Preset View](#creating-a-preset-view) that shows the data you need.

#### Default View icon

You may change the icon used for the Default View using the `favoritesBarDefaultIcon()` method:

```php
AdvancedTablesPlugin::make()
    ->favoritesBarDefaultIcon('heroicon-o-home')
```

To remove the Default View icon, don't pass anything to the method: `favoritesBarDefaultIcon()`

#### Divider

If using both Preset Views and User Views, it may be helpful to have a divider line to help users visually distinguish between the two. You may use the `favoritesBarDivider()` method to enable this:

```php
AdvancedTablesPlugin::make()
    ->favoritesBarDivider()
```

For more ways to distinguish between Preset Views and Users Views, please read the section [Distinguishing between Preset Views and Users Views](#distinguishing-between-preset-views-and-users-views)

#### Loading Indicator (New)

You may show a loading indicator when switching between views by using the `favoritesBarLoadingIndicator()` method:

```php
AdvancedTablesPlugin::make()
    ->favoritesBarLoadingIndicator()
```

#### Disabling the Favorites Bar

You can disable the Favorites Bar entirely (helpful if you only want to use [reorderable columns](#reorderable-columns-new)) by passing `false` to the `favoritesBarEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->favoritesBarEnabled(false)
```

You may also configure this per table by overriding the `favoritesBarIsEnabled()` method on your List page:

```php
class ListOrders extends ListRecords
{
    use AdvancedTables; 

    public static function favoritesBarIsEnabled(): bool
    {
        return false;
    }
    ...
```

You may also disable [Quick Save](#disabling-quick-save) or the [View Manager](#disabling-the-view-manager) if needed.

## Quick Save (New)

Advanced Tables offers a quick way for end-users to save User Views with the Quick Save button. Quick Save can be customized in a variety of ways to match the needs of your application.

### Quick Save configurations

Advanced Tables offers multiple ways to customize Quick Save. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`.

#### Disabling Quick Save

You may disable Quick Save entirely by passing `false` to the `quickSaveEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveEnabled(false)
```

You may also configure this per table by overriding the `quickSaveIsEnabled()` method on your List page:

```php
class ListOrders extends ListRecords
{
    use AdvancedTables; 

    public static function quickSaveIsEnabled(): bool
    {
        return false;
    }
    ...
```

If you wish to just hide the Quick Save button for certain users, you can also use [policies](#authorization).

You may also disable the [Favorites Bar](#disabling-the-favorites-bar) or the [View Manager](#disabling-the-view-manager) if needed.

#### Changing the icon

You may change the icon of the Quick Save button using the `icon` argument of the `quickSaveInFavoritesBar()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(icon: 'heroicon-o-bookmark')
```

> Note: The Quick Save icon only applies when the button is in the Favorites Bar.

#### Changing the position in the Favorites Bar

By default, Quick Save is at the end of the Favorites Bar. You may position it at the start of the Favorites Bar using the `quickSaveInFavoritesBar()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(position: 'start')
```

#### Displaying in the table toolbar

By default, Quick Save is displayed in the Favorites Bar. You may display it in the toolbar by passing `false` to the `quickSaveInFavoritesBar()` method and adding the quickSaveInTable() method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(false)
    ->quickSaveInTable()
```

#### Displaying as a modal

By default, Quick Save will open it's form in a slideOver. You may display the form in a modal by passing `false` to the `quickSaveSlideOver()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveSlideOver(false)
```

## View Manager (New)

Advanced Tables' View Manager is an easy and convenient way for your end-users to manage all of the views available for the table. Users can quickly search, apply, sort, edit, delete, add to favorites, and more, all from the View Manager. The View Manager can be customized in a variety of ways to match the needs of your application.

### Using the view manager

The View Manager allows end-users to access, apply, edit, sort, and manage all the available table views, including Preset Views, public views, and global favorites. Depending on which views are enabled, the view manager can display up to five different sections:

1. User favorites (includes: favorited Preset Views, favorited User Views, and global favorite views)
2. User views (non-favorited User Views)
3. Preset views (non-favorited Preset Views)
3. Public views (other user's public views)
4. Global views (global favorites that have been removed from the user's favorites)

#### Action button

Next to each view is an action button that gives the user several options depending on the type of view:

1. Apply view
2. Set as default/Remove as default ([NEW!](#managed-default-views-beta))
3. Add to favorites/Remove from favorites
4. Edit view (only displayed for the User Views created by the user)
5. Delete view (only displayed for the User Views created by the user)

#### Sorting views

User favorites, User views, and Preset views can be sorted by clicking the up/down arrows and then dragging/dropping the view to the desired location. Each view will be confined to it's section. 

> Important: If the User Favorites section contains both Preset Views and User Views, Preset Views will always come first, followed by User Views. These two types of views can only be sorted within their respective groupings. In other words, Preset Views can only be sorted among other Preset Views, and User Views can only be sorted among other User Views.

### View Manager configurations

Advanced Tables offers multiple ways to customize the View Manager. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`.

#### Changing the position in the Favorites Bar

By default, View Manager is displayed at the end of the Favorites Bar. You may position it at the start of the Favorites Bar using the `viewManagerInFavoritesBar()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerInFavoritesBar(position: 'start')
```

#### Displaying in the table toolbar

By default, View Manager is displayed in the Favorites Bar. You may display it in the toolbar by passing `false` to the `viewManagerInFavoritesBar()` method and adding the viewManagerInTable() method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerInFavoritesBar(false)
    ->viewManagerInTable()
```

#### Changing the position in the table toolbar

By default, View Manager is displayed after the search field. You may display at any of the tooldbar positions available via Filament's toolbar renderhooks by passing the renderhook to the `position` property in the `viewManagerInTable()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerInTable(position: 'tables::toolbar.toggle-column-trigger.before')
```

#### Displaying as a button with a label

By default, View Manager is displayed as a icon button. You may display it as a button with a label by using the `viewManagerButton()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerButton(label: 'Views')
```

#### Changing the button and icon size

You may change the size of the View Manager's button and icon using the `viewManagerButtonSize()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerButtonSize('lg')
```

#### Displaying the button outlined

If you are displaying the View Manager as button you may display it outlined by using the `viewManagerButtonOutlined()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerButtonOutlined()
```

#### Displaying as a SlideOver

By default, View Manager is displayed as a dropdown. You may display it as a slideOver by adding the `viewManagerSlideOver()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerSlideOver()
```

##### Dropdown vs slideOver internally

Internally, when displaying View Manager as a slideOver, Advanced Tables only has to query and select from the database the user's *favorite* views as they are the only views show in the table. Since Filament only processes the content in slideOvers when they are triggered by an action button, the remaining views aren't queried until the View Manager is triggered. This helps reduce unnecessary memory usage by selecting a smaller dataset from the database. 

However, this also means that when opening a slideOver there is a slight delay as Filament has to then query the database. 

On the flip side, when displaying the View Manager as a dropdown, Advanced Tables has to query and select all the available views from the database. This is because dropdowns already load all the data and are simply hidden and shown in Alpine. 

This in turn means that there is additional memory usage as all of the table's views are queried from the database and loaded into memory. However, it also means that opening the dropdown is instant as opposed to having a delay with the slideOver.

In most situations, the additional memory usage of the dropdown is worth the tradeoff to have the View Manager instantly available, but knowing how this works internally will help you decide which is best for your application.

#### Disabling the View Manager

You may disable the View Manager entirely by passing `false` to the `viewManagerEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerEnabled(false)
```

You may also configure this per table by overriding the `viewManagerIsEnabled()` method on your List page:

```php
class ListOrders extends ListRecords
{
    use AdvancedTables; 

    public static function viewManagerIsEnabled(): bool
    {
        return false;
    }
    ...
```

You may also disable the [Favorites Bar](#disabling-the-favorites-bar) or [Quick Save](#disabling-quick-save) if needed.

#### Changing the icon

You may change the icon used for the View Manager using the `viewManagerIcon()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerIcon('heroicon-o-bars-3')
```

#### Icon position

You may change the position of the icon in the View Manager using the `viewManagerIconPosition()` method:

```php
use Filament\Support\Enums\IconPosition;

AdvancedTablesPlugin::make()
    ->viewManagerIconPosition(IconPosition::After)
```

#### Hiding the active view badge indicator

When displaying the View Manager as a dropdown, by default a badge indicator will be shown when there is an active View. You may disable the badge by passing `false` to the `viewManagerBadge()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerBadge(false)
```

> Note: The active view badge indicator is only available when the View Manager is used as a dropdown.

#### Hiding the search field

By default the View Manager includes a search field to quickly search for views. You may disable the search field by passing `false` to the `viewManagerSearch()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerSearch(false)
```

#### Displaying a Save View link

You may include a Save View link inside the View Manager with the `viewManagerSaveView()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerSaveView()
```

This also allows you to hide the Quick Save button from the Favorites Bar to maximize the space available in the Favorites Bar:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(false)
    ->viewManagerInFavoritesBar(false)
    ->viewManagerInTable()
    ->viewManagerSaveView()
```

> Note: This option is only available when the View Manager is displayed as a dropdown. When displaying the View Manager as a slideOver, `viewManagerSaveView()` has no effect.

#### Displaying a Reset link

You may include a Reset link inside the View Manager that functions the same as clicking the [`Default View` button](#default-view) with the `viewManagerResetView()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerResetView()
```

This also allows you to [hide Default View button](#disabling-the-default-view) from the Favorites Bar to maximize the space available in the Favorites Bar.

#### Disabling Click to Apply

By default a user may click on any of the Views in the View Manager to apply that view's configuration to the table. You may disable this by passing `false` to the `viewManagerClickToApply()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerClickToApply(false)
```

#### Hiding the Apply button

By default a View's action button includes an `Apply View` button to apply that view's configuration to the table. You may hide this by passing `false` to the `viewManagerApplyButton()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerApplyButton(false)
```

#### Hiding the Active View Indicator

By default the View Manager will display an indicator next to the currently active view. You may hide this by passing `false` to the `viewManagerActiveViewIndicator()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerActiveViewIndicator(false)
```

#### Displaying the Active View indicator a badge

By default the View Manager will display the active view indicator as a small green dot next to the current active view. You may change this to be a badge with the `viewManagerActiveViewBadge()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerActiveViewBadge()
```

The name of the badge can be modified in the [language file](#language-files).

#### Hiding the view type icons

Since different types of views have different available options, by default the View Manager will display view type icons next to each view. The icons that can be displayed are:

- Preset Views - lock icon
- Views a user created - user icon
- Public views - eye icon
- Global views - globe icon

If you wish to hide these icons you can pass `false` to the `viewManagerViewTypeIcons()` method:
 
```php
AdvancedTablesPlugin::make()
    ->viewManagerViewTypeIcons(false)
```

#### Displaying view types as badges

If you prefer to display view types as badges instead of icons you can use the `viewManagerViewTypeBadges()` method: 
 
```php
AdvancedTablesPlugin::make()
    ->viewManagerViewTypeBadges()
```

#### Displaying both public and global view type indicators

By default, when a view is both public and a global favorite, the View Manager will only show the global favorite indicator, be it the icon or the badge. This helps reduce visual clutter as global favorites are already public. However, if you wish to display both you may do so with the `viewManagerPublicIndicatorWhenGlobal()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerPublicIndicatorWhenGlobal()
```

#### Hiding the user icon

By default the View Manager will display the chosen icon for User Views and Preset Views in the View Manager. You may hide this icon in the View Manager with the `viewIcon()` method:

```php
AdvancedTablesPlugin::make()
    ->viewIcon(false)
```

#### Changing the default view icon

If there is no icon associated with the User View or Preset View, a default icon will be shown in the View Manager. You may change which icon is displayed with the `defaultViewIcon()` method:

```php
AdvancedTablesPlugin::make()
    ->defaultViewIcon('heroicon-o-queue-list')
```

## Reorderable Columns (New)

Advanced Tables enhances Filament's [toggleable columns](https://filamentphp.com/docs/3.x/tables/columns/getting-started#toggling-column-visibility) dropdown with powerful column reordering. Now you and your users can move hide, show, and move columns to create a totally custom view. Best of all, when a user creates a new User View, their new column order is saved as well. 

> Note: When using a table with a [column layout](https://filamentphp.com/docs/3.x/tables/layout), the columns dropdown will not show the reorder button since columns cannot be reordered in this type of layout.

### Reordering columns

To reorder columns:

1. Click the toggle column button in the table toolbar to open the column dropdown. 
2. Click the `up/down arrow` button to enable reordering
3. Drag and drop your columns in the order you prefer.

> Note: At least one column in your table must be `toggleable()` for Filament to display the toggle column button.

### Reorderable Columns configurations

Advanced Tables offers multiple ways to customize Reorderable Columns. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`. 

#### Disabling column reordering

Advanced Tables enables column reordering by default. You may disable this and use Filament's native column toggling UI by passing `false` to the `reorderableColumnsEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->reorderableColumnsEnabled(false)
```

You may also disable Reorderable Columns per resource by overriding the `canReorderColumns()` method in the class where you have added the AdvancedTables trait:

```php
public function canReorderColumns(): bool
{
    return false;
}
```

#### Always displaying the hidden label

By default, the enhanced toggle column dropdown will only display the `Hidden` label when there are hidden columns. To always display the hidden label you may use the `reorderableColumnsAlwaysDisplayHiddenLabel()` method:

```php
AdvancedTablesPlugin::make()
    ->reorderableColumnsAlwaysDisplayHiddenLabel()
```

#### Display the toggle column dropdown as two columns

You may show the toggle column dropdown as two columns by using the `columnToggleFormColumns()` method on your table:

```php
public static function table(Table $table): Table
{
    return $table
        ->columns([
            ...
        ])
        ->columnToggleFormColumns(2)
```

#### Configuring the icons

You may change any of the icons used for Reorderable Columns by using the following methods:

```php
AdvancedTablesPlugin::make()
    ->reorderIcon('heroicon-m-arrows-up-down')
    ->checkMarkIcon('heroicon-m-check')
    ->dragHandleIcon('heroicon-o-bars-2')
    ->visibleIcon('heroicon-s-eye')
    ->hiddenIcon('heroicon-o-eye-slash')
```

To remove any of the icon, don't pass anything to the the respective method: `->hiddenIcon()`

## Managed Default Views (Beta)

![Default Views](https://advancedtables.com/images/default-views.png)

Advanced Tables now allows your users to manage which view they would like to be their default view for each table. When a view is a default it will be automatically loaded when the resource/table is first opened after logging in.

### Updating to the Managed Default Views Beta

1. Update to the beta

    If you are on version 3.8 and only want to experiment with Managed Default Views, update your `composer.json` file to:

    ```json
    "archilex/filament-filter-sets": "~3.9.0@beta-beta.1",
    ```

    If you want to experiment with Managed Default Views, [Multi-Sort](#multi-sort-beta), and [Advanced Indicators](#advanced-indicators-beta), update your `composer.json` file to:

    ```bash
    "archilex/filament-filter-sets": "^3.10@beta",
    ```

2. Publish and run the migrations:

    ```bash
    php artisan vendor:publish --tag="advanced-tables-migrations"
    php artisan migrate
    ```

3.  If you are using [multi-tenancy](#multi-tenancy) run the following command to add the appropriate constraints. If not, you can skip this: 

    ```bash
    php artisan advanced-tables:add-tenancy
    ```

4. Compile assets

    After updating run `npm run build` and `php artisan filament:upgrade`.

5. Enable Managed Default Views

    Managed Default Views are disabled by default. To enable, add `managedDefaultViewsEnabled()` to your panel provider:

    ```php
    AdvancedTablesPlugin::make()
        ->managedDefaultViewsEnabled()
    ```

### Using Managed Default Views

To use Managed Default Views:

1. Open the [View Manager](#view-manager-new).
2. Next to the view you would like to make default, click the action group button then choose, "Set default".
3. You may also remove a view as a default view. If there is a matching developer-defined [default Preset View](#loading-a-default-preset-view), it will become the new default.

### UX Recommendation

Advanced Tables comes with an basic "Default" view that is automatically added to each table. However, this default view is an internal "view" and does not display in the View Manager. To offer the clearest UX to your end-users and the best compatibility with Managed Default Views, it is recommended to disable this internal default view, and to add a default Preset View to each of your pages. You can accomplish this by:

1. Disable the internal default view:
    
    ```php
    AdvancedTablesPlugin::make()
        ->favoritesBarDefaultView(false)
    ```

2. Add a default Preset View to your list pages:

    ```php
    public function getPresetViews(): void
    {
        return [
            'default' => PresetView::make()
                ->default()
                ->favorite()
                ->icon('heroicon-o-bars-4')
        ];
    }

> Note: Starting in the upcoming v4, the internal default view will be removed in favor of a default Preset View.

## Multi-Sort (Beta)

![Multi-Sort](https://advancedtables.com/images/multi-sort.png)

Advanced Tables now allows your users to sort their tables by multiple columns. Using the new Multi-Sort dropdown, users can add additional columns to sort by, easily change sort direction, and even reorder the columns. And Multi-Sort is completely integrated with [Preset Views](#preset-views) and [User Views](#user-views).

### Updating to the Multi-Sort Beta

1. Update to the beta

    To update to the beta update your `composer.json` file to:

    ```json
    "archilex/filament-filter-sets": "^3.10@beta",
    ```

2. Compile assets

    After updating run `npm run build` and `php artisan filament:upgrade`.

3. Install Default Views (optional)

    If you would also like to use the new Default Views, [follow these instructions](#updating-to-the-managed-default-views-beta).

### Using Multi-Sort

To use multi-sort:

1. Click the new multi-sort button in the table toolbar to open the multi-sort dropdown.
2. Click the `Add column` button to add a column to sort by. Only `->sortable()` table columns will be shown.
3. Use the `up` and `down` arrow buttons to change the sort direction.
4. You may add additional columns and then drag and drop the them in the order you prefer.

### Using with Preset Views 

You can apply multi-sorting in your [Preset Views](#preset-views) through the `defaultSort()` method:

```php
'processing' => PresetView::make()
    ->defaultSort([
        'is_visible' => 'desc',
        'price' => 'asc'
    ])
```

### Multi-Sort configurations

Advanced Tables offers multiple ways to customize Multi-Sort. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`.

#### Disabling Multi-Sort

Advanced Tables enables multi-sorting by default. You may disable this by passing false to the `multiSortEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->multiSortEnabled(false)
```

#### Changing the icon

You may change the icon used for the Multi-Sort dropdown using the `multiSortIcon()` method:

```php
AdvancedTablesPlugin::make()
    ->multiSortIcon('heroicon-s-chevron-up-down')
```

#### Hiding the badge

By default, when one or more columns is being sorted, the Multi-Sort dropdown button will display a badge indicating the number of columns that are being sorted. You may hide the badge by passing `false` to the `multiSortBadge()` method:

```php
AdvancedTablesPlugin::make()
    ->multiSortBadge(false)
```

#### Customizing the buttons and labels
You may customize Multi-Sort buttons, labels in the language file.

## Advanced Indicators (Beta)

![Advanced indicators](https://advancedtables.com/images/advanced-indicators.png)

> Important: Advanced Indicators is one of the biggest additions to Advanced Tables since it's initial launch and I'm very excited to be able to bring this functionality to Filament. However, since there are still [outstanding features](#specifying-favorite-filters-with-user-views-under-development) to be implemented, [known limitations](#current-limitations-and-unknowns) that are under development, and there may be custom Filament implementations that haven't been accounted for, I am launching this as a beta feature. Please read all the instructions fully to know what is currently supported, what is under development, and what may not be supported. If you do find an issue, please reach out to me on discord our through email.

Advanced Indicators gives your users quick access to their filters through Filament's indicator system. When enabled, each indicator can be clicked on to access that filter's settings. In addition, filters can be favorited and "pinned" so they always appear, even when not active. 

### Updating to the Advanced Indicators Beta

1. Update to the beta

    To update to the beta update your `composer.json` file to:

    ```bash
    "archilex/filament-filter-sets": "^3.10@beta",
    ```

2. Compile assets
    
    After updating be sure to run `npm run build` and `php artisan filament:upgrade`.

3. Update Custom Filter Classes

    Advanced Indicators automatically overrides any default Filament filters you have included in your resource or page. However, any custom filter classes that you have created that extends a Filament filter will need to be updated to use Advanced Table's versions. This can be easily accomplished by just updating your imported class with the plugins equivalent:

    ```php
    - use Filament\Tables\Filters\Filter
    + use Archilex\AdvancedTables\Filament\Filter

    - use Filament\Tables\Filters\SelectFilter
    + use Archilex\AdvancedTables\Filament\SelectFilter

    - use Filament\Tables\Filters\TernaryFilter
    + use Archilex\AdvancedTables\Filament\TernaryFilter

    - use Filament\Tables\Filters\TrashedFilter
    + use Archilex\AdvancedTables\Filament\TrashedFilter
    ```

    Remember, you only need to override *custom* filter classes you have created. Filters used within Filament's resources and pages will be overridden automatically.

4. Enable Advanced Indicators

    Advanced Indicators is disabled by default. To enable, add `advancedIndicatorsEnabled()` to your panel provider:

    ```php
    AdvancedTablesPlugin::make()
        ->advancedIndicatorsEnabled()
    ```

5. Add the AdvancedTables trait

    If you haven't already, [add the AdvancedTables trait](#adding-advanced-tables-to-your-table) to your table.

6. Install Managed Default Views (optional)

    If you would also like to use the new Managed Default Views, [follow these instructions](#updating-to-the-managed-default-views-beta).

### Using Advanced Indicators

Once enabled, Advanced Indicators should work right out the box with minimal configuration. Just click on any indicator to see the form field(s) associated with that filter. Any adjustments to that filter will be immediately reflected in the table and synced to filament's filter form. 

#### Custom Filters with Multiple Form Fields

When implementing custom filters with multiple form fields in Filament, there are two main ways to display the indicator(s). You could display a single indicator that adapts according to the fields that are set, or you could have individual indicators for each field. As an example, take the following date filter examples which have two date fields, but display the indicator differently.

**Example 1 - Display as a single indicator:**

![Single indicator](https://advancedtables.com/images/single-indicator.png)

```php
Filter::make('created_at')
    ->form([
        DatePicker::make('created_from'),
        DatePicker::make('created_until'),
    ])
    ->query(function (Builder $query, array $data): Builder {
        ...
    })
    ->indicateUsing(function (array $data): ?Indicator {                        
        if (($data['created_from'] ?? null) && (! ($data['created_until'] ?? null))) {
            return Indicator::make('Created from ' . Carbon::parse($data['created_from'])->toFormattedDateString());
        } 

        if ((! ($data['created_from'] ?? null)) && ($data['created_until'] ?? null)) {
            return Indicator::make('Created until ' . Carbon::parse($data['created_until'])->toFormattedDateString());
        } 

        if (($data['created_from'] ?? null) && ($data['created_until'] ?? null)) {
            return Indicator::make('Created between ' . Carbon::parse($data['created_from'])->toFormattedDateString() . ' and ' . Carbon::parse($data['created_until'])->toFormattedDateString());
        }

        return null;
    })
```

**Example 2 - Display as multiple indicators:**

![Multiple indicators](https://advancedtables.com/images/multiple-indicators.png)

```php
Filter::make('published_at')
    ->form([
        DatePicker::make('published_from'),
        DatePicker::make('published_until'),
    ])
    ->query(function (Builder $query, array $data): Builder {
        ...
    })
    ->indicateUsing(function (array $data): array {                        
        $indicators = [];

        if ($data['published_from'] ?? null) {
            $indicators[] = Indicator::make('Published from ' . Carbon::parse($data['published_from'])->toFormattedDateString())
                ->removeField('published_from');
        }

        if ($data['published_until'] ?? null) {
            $indicators[] = Indicator::make('Published until ' . Carbon::parse($data['published_until'])->toFormattedDateString())
                ->removeField('published_until');
        }

        return $indicators;
    }),
```

Advanced Indicators supports both of these use cases. In the first example, only one indicator will be shown, but the form will include both fields. In the second, only the indicator's respective field will be displayed. 

If you are using return types (and you should be) then Advanced Indicators will automatically detect how the indicators should be displayed. If you are not using return types, then you will need to be explicit about how Advanced Indicators should display your form fields using the `->multipleIndicators()` method:

**Example 1 - Display as a single indicator:**

```php
Filter::make('created_at')
    ->multipleIndicators(false)
```

**Example 2 - Display as multiple indicators:**

```php
Filter::make('created_at')`
    ->multipleIndicators()
```

> Note: Displaying indicators outside of these two examples (ie. a single indicator for all form fields, or a one-to-one field/indicator setup), is not currently supported. If you have a filter set up like this, please contact me. 

#### Favorite Filters

![Favorite filters](https://advancedtables.com/images/favorite-filters.png)

Advanced Indicators not only gives you quick access to applied filters, but also allows you to specify "favorite" filters which will always be displayed in the indicator bar, even when the filter is not active. You can make a filter a favorite by using the `->favorite()` method:

```php
SelectFilter::make('brand')
    ->favorite()
```

>Note: Support for Filament's `->columns()` method on filters is coming soon.

#### Limiting the Indicator labels

![Advanced indicators](https://advancedtables.com/images/advanced-indicators.png)

Advanced Indicators also introduces the ability to limit the number of labels that are shown on a Select Filter. Since you now have easy access to filters through the indicator, it may not be necessary to pollute the indicator bar with an excessively long indicator. To limit the indicator labels you may use the `->limitIndicatorLabels()` method:

```php
SelectFilter::make('brand')
    ->limitIndicatorLabels(3)
```

By default, once the limit is reached Filament's localized version of `& 3 more` will be displayed. However, you may change this by publishing and updating the plugin's language files and updating the `more_indicator_labels` value in the `advanced-tables.php` language file:

```php
'indicators' => [
    'more_indicator_labels' => '+ :count', // display as "+ 4"
],
```

#### Specifying Favorite Filters in Preset Views

If you are using [Preset Views](#preset-views) you may configure which filters should be displayed as favorites using the `->defaultFavoriteFilters()` method:

```php
'recentlyCreated' => PresetView::make()
    ->favorite()
    ->defaultFavoriteFilters(['created_at'])
    ->defaultFilters([
        'created_at' => [
            'created_from' => now()->startOfWeek()->toDateString(),
            'created_until' => now()->endOfWeek()->toDateString(),
        ],
    ])
```

> Note: When defining default favorite filters, the order of the filters will be determined by the order they are in listed in Filament's ->filters() array. Support for ordering by the order of the ->defaultFavoriteFilters() array is coming.

#### Specifying Favorite Filters with User Views (Under Development)

User-specified favorite filters is currently under development and should be released soon. When released, your users will be able to favorite, rearrange, and even hide filters according to their needs and then save that configuration as a [User View](#user-views).

#### Deferring Advanced Indicators

The current implementation of Advanced Indicators is for each indicator form to be live even if you are using Filament's [filter deferring](https://filamentphp.com/docs/3.x/tables/filters/getting-started#deferring-filters). Since each indicator is a subset of all the filters, deferring a single filter doesn't seem necessary.

However, if there is sufficient demand/need for it, I will look into bringing deferring to Advanced Indicators in the future. If implemented, each indicator dropdown would have it's own "Apply" button. Please contact me if this is a feature you need.

### Current Limitations and Unknowns

While Advanced Indicators should work for the majority of implementations, there are currently a few limitations and unknowns:

1. [Advanced Filter Builder](#advanced-filter-builder-new) is not currently supported, but under development.
2. Custom filters may not be fully supported, but the goal is to support any implementation with Filament's filters. If something is not working as expected please contact me.
3. Third-party filter plugins have not been tested. If a filter plugin is not working, please contact me. Please note, that full support may require the plugin developer to update their filter. 
4. Filament's Query Builder Filter is not currently supported. I am looking into supporting it, but if support comes it will be at the very end of this development period.

### Disabling Advanced Indicators

If you wish to disable Advanced Indicators, you may pass false to the `->advancedIndicatorsEnabled()` method:

```php
AdvancedFilter::make()
    ->advancedIndicatorsEnabled(false)
```

## Advanced Filter Builder (New)

![Advanced filter builder](https://user-images.githubusercontent.com/6097099/278955775-f124d155-8fd8-4af5-bf38-e13ec958df3c.png)

Advanced Filter Builder is a custom filtering system that gives your users a simple, yet powerful way to quickly build custom queries. Each filter inside the builder can be used multiple times and grouped into *or groups*, allowing your users to drill down and find the data they need. Advanced Filter Builder was designed to make filtering easy for your users with a simple UI and natural filtering language. 

For developers, Advanced Filter Builder couldn't be easier to implement. Advanced Filter Builder can *automatically* generates `text`, `numeric`, `date`, `boolean`, and `select` filters from your table columns! You can also seamlessly integrate your existing filters or override the auto-generated ones allowing you to fully customize the filtering experience.

> Important: [Adding AdvancedTables](#adding-advanced-tables-to-your-table) to your table is required for Advanced Filter Builder to properly work.

### Using Advanced Filter Builder

To enable the Advanced Filter Builder, add `AdvancedFilterBuilder` to your table's `->filter()` method:

```php
return $table
    ->columns([
        ...
    ])
    ->filters([
        AdvancedFilter::make(),
    ])
```

### Enabling Column Filters

<img src="https://user-images.githubusercontent.com/6097099/278954852-3a754833-d7a7-414c-a7fc-2dbe52e53b79.jpg" alt="Column Filters" width="600"/>

To automatically generate Column Filters for each of your table columns, you may use the `->includeColumns()` method. This will [automatically map](#automatic-column-mapping) your table's compatible columns to the appropriate [Column Filter](#column-filter-types) and make them available in Advanced Filter Builder's picker:

```php
AdvancedFilter::make()
    ->includeColumns()
```

>Tip: If you wish to only use some Column Filters, you may use either [include](#including-columns) or [exclude](#excluding-columns) columns.

### Column Filter types

Advanced Filter Builder includes multiple different custom Column Filters, each with it's own set of operators:

#### Text Filter

The `TextFilter` allows you to filter text strings with operators like `is`, `is not`, `starts with`, `does not end with`, `contains`, etc.

<img src="https://user-images.githubusercontent.com/6097099/278954866-658a0990-335e-4fb8-b554-3de42e469592.jpg" alt="Text Filter" width="600"/>

When appropriate, the `TextFilter` can also transform the `is` and `is not` operators into a multiple select dropdown:

<img src="https://user-images.githubusercontent.com/6097099/278954865-2539f10e-3ec9-4445-8484-c9bafeaa7952.jpg" alt="Text Filter with select" width="600"/>

#### Numeric Filter

The `NumericFilter` allows you to filter numbers with operators like `equal to`, `greater than`, `less than or equal to`, `between`, `positive`, etc.

<img src="https://user-images.githubusercontent.com/6097099/278954861-0740435e-244b-4355-9a31-b109fe9b4a41.jpg" alt="Numeric filter" width="600"/>

#### Date Filter

The `DateFilter` allows you to filter dates combining *operators* like `yesterday`, `in the next`, `before`, `between`, etc. with *units* like `day`, `week`, `months ago`, `years from now`, etc.

<img src="https://user-images.githubusercontent.com/6097099/278954859-f4486c21-6a30-429f-8d45-4f96a8ae2275.jpg" alt="Date filter" width="600"/>

#### Select Filter

Advanced Table's custom `SelectFilter` combines Filament's `SelectFilter` with operators `is`, `is not`, `is empty`, `is not empty`.

<img src="https://user-images.githubusercontent.com/6097099/278954856-68f48126-a400-4801-a2b7-459a4c59c391.jpg" alt="Select filter" width="600"/>

### Automatic column mapping

Advanced Filter Builder will automatically map your table columns to the appropriate filter depending on the type of column:

1. `TextColumn::make()->date()` and `TextColumn::make()->dateTime()` columns will be mapped to the [DateFilter](#date-filter).
2. `TextColumn::make()->numeric()` and `TextColumn::make()->money()` columns will be mapped to the [NumericFilter](#numeric-filter).
3. [Aggregate Relationship](https://filamentphp.com/docs/3.x/tables/columns/relationships) columns `count`, `avg`, `min`, `max`, and `sum` will be mapped to an aggregate [NumericFilter](#numeric-filter).
4. Any remaining `TextColumn` will be mapped to the [TextFilter](#text-filter).
5. `SelectColumn` will be mapped to Advanced Filter's custom [SelectFilter](#select-filter).
6. `CheckboxColumn`, `ToggleColumn`, `ImageColumn`, `IconColumn` will be mapped to Filament's `Ternary Filter`.

### Customizing filters

Advanced Filter Builder uses the methods on your columns to automatically determine the appropriate filter to use. However, sometimes your table column may not match the type of filter you need. For example, if you are using a `TextColumn` to display an numeric amount, but aren't using the `->numeric()` method, Advanced Filter Builder wouldn't know it's best to use a `NumericFilter`. In these cases, it's easy to customize the filter manually using the `->filters()` method.

#### Customizing a Column Filter

You may manually define a Column Filter for a particular column by passing the desired [filter type](#column-filter-types) to the `->filters()` method. The `name` of the filter should be the column you wish to override.

> Tip: Any filter you add to the `->filters()` array will be shown in the filters dropdown by default. To override this behavior you can use the `->defaultFilters()` method to [configure](#setting-the-default-filters) which filters, if any, are shown by default.

> Note: When you are customizing a Column Filter the `name` of the filter *must* match the name of the column in your Filament table. If not, it will not appear in the Filter Picker.

```php
AdvancedFilter::make()
    ->filters([
        NumericFilter::make('shipping_price') // Use the NumericFilter on the shipping_price column
    ])
```

To enable the `Select` field inside of the `TextFilter`, you may use a `TextFilter` and then pass in an array of options:

```php
AdvancedFilter::make()
    ->filters([
        TextFilter::make('country')
            ->options(fn () => Country::all()->pluck('name', 'id')),
    ])
```

You may also pass in a relationship to automatically load the available options:

```php
AdvancedFilter::make()
    ->filters([
        TextFilter::make('customer.name')
            ->relationship(name: 'customer', titleAttribute:'name')
            ->multiple()
            ->preload(),
    ])
```

Finally, if your table column only needs a dropdown of options to select from (ie, it doesn't need additional operators like `starts with`, `contains`, etc.), you may manually map your column to Advanced Filter Builder's custom `SelectFilter`:

```php
use Archilex\AdvancedTables\Filters\SelectFilter;

AdvancedFilter::make()
    ->filters([
        SelectFilter::make('status')
            ->options([
                'processing' => 'Processing',
                'new' => 'New',
                'shipped' => 'Shipped',
                'delivered' => 'Delivered',
                'cancelled' => 'Cancelled',
            ])
            ->multiple(), 
    ])
```

> Important: Be sure to import `Archilex\AdvancedTables\Filters\SelectFilter` to see the `is`, `is not`, `is empty`, and `is not empty` operators.

##### Customizing a column filter's operators

You may customize a column filter's operators using either the `->includeOperators()` or `->excludeOperators()` methods:

```php
AdvancedFilter::make()
    ->filters([
        TextFilter::make('name')
            ->includeOperators([
                TextOperator::CONTAINS,
                TextOperator::DOES_NOT_CONTAIN
            ]), 
        SelectFilter::make('status')
            ->includeOperators([
                TextOperator::IS, // The SelectFilter uses the TextOperator
            ]), 
        DateFilter::make('created_at')
            ->excludeOperators([
                DateOperator::YESTERDAY,
                DateOperator::TODAY,
                DateOperator::TOMORROW
            ]), 
        NumericFilter::make('total_price')
            ->excludeOperators([
                NumericOperator::EQUAL_TO,
                NumericOperator::NOT_EQUAL_TO
            ]),
    ])
```

To customize a column filter's operators globally, you can call the static `configuringUsing()` method from the `boot()` method of a service provider:

```php
public function boot()
{
    TextFilter::configureUsing(function (TextFilter $filter) {
        return $filter->includeOperators([
            TextOperator::CONTAINS,
            TextOperator::DOES_NOT_CONTAIN
        ]);
    });
}
```

`includeOperators()` and `excludeOperators()` can also take a closure meaning you can further customize which operators are available:

```php
TextFilter::configureUsing(function (TextFilter $filter) {
    return $filter->includeOperators(function (TextFilter $filter) {
        return $filter->getName() === 'currency'
            ? [TextOperator::CONTAINS, TextOperator::DOES_NOT_CONTAIN]
            : [TextOperator::IS, TextOperator::IS_NOT];
    });
});
```

##### Customizing a column filter's default operator

To customize a column filter's default operator you may pass the name of the operator to the `->defaultOperator()` method:

```php
AdvancedFilter::make()
    ->filters([
        TextFilter::make('name')
            ->defaultOperator(TextOperator::CONTAINS),
    ])
```

To customize a column filter's default operator globally, you can call the static `configuringUsing()` method from the `boot()` method of a service provider:

```php
public function boot()
{
    TextFilter::configureUsing(fn (TextFilter $filter) => $filter->defaultOperator(TextOperator::CONTAINS));
    DateFilter::configureUsing(fn (TextFilter $filter) => $filter->defaultOperator(DateOperator::TODAY));
    SelectFilter::configureUsing(fn (TextFilter $filter) => $filter->defaultOperator(TextOperator::IS));
    NumericFilter::configureUsing(fn (TextFilter $filter) => $filter->defaultOperator(NumericOperator::GREATER_THAN));
}
```

`defaultOperator()` can also take a closure meaning you can further customize which operator is the default:

```php
TextFilter::configureUsing(function (TextFilter $filter) {
    return $filter->defaultOperator(function (TextFilter $filter) {
        return $filter->getName() === 'currency' 
            ? TextOperator::CONTAINS 
            : TextOperator::IS;
    }); 
});
```

#### Adding custom filters

Advanced Filter Builder can also seamlessly integrate any of Filament's [filters](https://filamentphp.com/docs/3.x/tables/filters), including [custom filters](https://filamentphp.com/docs/3.x/tables/filters#custom-filter-forms). This allows a filter to be used multiple times as well as in "or groups". 

> Tip: Any filter you add to the `->filters()` array will be shown in the filters dropdown by default. To override this behavior you can use the `->defaultFilters()` method to [configure](#setting-the-default-filters) which filters, if any, are shown by default.

To add a filter to Advanced Filter Builder, pass the filter into the `->filters()` method:

```php
AdvancedFilter::make()
    ->filters([
        Filter::make('is_active')
            ->query(fn (Builder $query): Builder => $query->where('is_active', true))
            ->toggle(),
    ])
```

> Note: Any filter that has the same `name` as your table column, will be override the automatically mapped column filter. If the filter name does not match any of the table columns it will be added as an additional filter.

> Important: If you are updating from a prior release and your users have already saved created User Views with filters, don't worry, Advanced Filter Builder will automatically map them to the first filter group.
>
> However, if you are using Preset Views with [default filters](#applying-filters-new), you will need to [adjust your filters](#applying-filters-with-filter-builder-new) to be compatible with Advanced Filter Builder.

### Using filters alongside Advanced Filter Builder

You may still use any of Filament's filters alongside Advanced Filter Builder by adding it as you normally would to your table's `->filters()` method:

```php
return $table
    ->columns([
        ...
    ])
    ->filters([
        Filter::make('is_active')
            ->query(fn (Builder $query): Builder => $query->where('is_active', true))
            ->toggle(),
        AdvancedFilter::make(),
    ])
```

The above will add a *single* `Is active` toggle filter to the filter dropdown as well as display the Advanced Filter Builder below it.

### Including columns

To only filter some of your columns, you may pass an array of column `names` you wish to include to the `->includeColumns()` method:

```php
AdvancedFilter::make()
    ->includeColumns([
        'is_active',
        'currency',
        'address.city',
    ]);
```

> Important: If you are [customizing a Column Filter](#customizing-a-column-filter), that column must be included in the `->includesColumns()` method.

### Excluding columns

You may instead exclude columns by passing an array of columns `names` to the `->excludeColumns()` method:

```php
AdvancedFilter::make()
    ->excludeColumns([
        'status',
        'customer.name',
        'created_at',
    ]);
```

> Important: If you are [customizing a Column Filter](#customizing-a-column-filter), that column must *not* be excluded from the `->excludesColumns()` method.

### Setting the default filters

By default, every filter included in Advanced Filter Builder's `->filters()` method will be shown in the table's filter dropdown. Column Filters that haven't been overriden in the `->filters()` method will be available in the filter picker. To not display any column filters you can pass an empty array to the `->defaultFilters()` method:

```php
AdvancedFilter::make()
    ->filters([
        ...
    ])
    ->defaultFilters([])
```

To only display some filters by default, you may pass the name of your filter to the `->defaultFilters()` method inside a double array. You may also use this method to define Column Filters you wish to be displayed by default in the filter dropdown:

```php
AdvancedFilter::make()
    ->filters([
        ...
    ])
    ->defaultFilters([['status']])
```

> Important: Be sure to add your filters inside a double array.

You can also set up multiple default groups:

```php
AdvancedFilter::make()
    ->filters([
        ...
    ])
    ->defaultFilters([['status'], ['status']])
```

### Disabling Or Groups

By default, Advanced Filter Builder allows your filters to be used in "or groups". You may disable this feature by passing `false` to the `->orGroups()` method:

```php
AdvancedFilter::make()
    ->orGroups(false)
```

### Layout options

Advanced Filter Builder responsively adapts to any of the available [FilterLayouts](https://filamentphp.com/docs/3.x/tables/filters#displaying-filters-in-a-modal) (`AboveContent`, `BelowContent`, `AboveContentCollapsible`, `Modal`, `SlideOver`, `Dropdown`). When the builder is used with the `Dropdown` layout (Filament's default layout), the user will also be presented with an "Expand View" button that will allow the dropdown to expand into a slideOver.

If you using the `Modal` layout, it's recommended you set the `->filtersFormWidth()` on the table to at least `3xl` so the form elements have space to flow:

```php
use Archilex\AdvancedTables\Filters\AdvancedFilter;
use Filament\Tables\Actions\Action;
use Filament\Tables\Table;
use Filament\Tables\Enums\FiltersLayout;
 
public function table(Table $table): Table
{
    return $table
        ->filters([
            AdvancedFilter::make(),
        ])
        ->filtersLayout(FiltersLayout::Modal)
        ->filtersFormWidth('3xl')
}
```

### Customizing the Expand View Link Position

When using Filament's default `Dropdown` filter layout, the user will also be presented with an "Expand View" button that will allow the dropdown to expand into a slideOver. The expand view link in this view is `absolute` positioned (ugly...I know). If you are using translatable fields, this may cause the link to overlap. You may change the position of the expand view link by passing an array of styles to the `->filterBuilderExpandViewStyles()` method:

```php
AdvancedTablesPlugin::make()
    ->filterBuilderExpandViewStyles(['right: 100px', 'top: 24px'])
```

This method also take a closure allowing you to set different positions based on a condition such as locale:

```php
use Illuminate\Support\Facades\App;

AdvancedTablesPlugin::make()
    ->filterBuilderExpandViewStyles(fn () => App::isLocale('es') ? ['right: 100px', 'top: 24px'] : ['right: 80px', 'top: 24px'])
```

### Always opening the filter as a slideOver

If you would prefer Advanced Filter Builder to always open in a slideOver or modal, you may use [Filament's](https://filamentphp.com/docs/3.x/tables/filters#customizing-the-filters-dropdown-trigger-action) `filtersTriggerAction()` method:

```php
use Archilex\AdvancedTables\Filters\AdvancedFilter;
use Filament\Tables\Actions\Action;
use Filament\Tables\Table;
 
public function table(Table $table): Table
{
    return $table
        ->filters([
            AdvancedFilter::make(),
        ])
        ->filtersFormWidth('md')
        ->filtersTriggerAction(
            fn (Action $action) => $action
                ->slideOver()
        );
}
```

### Adding icons to the Filter Picker

You can add icons to the Filter Picker by passing an array of icons to the `->icons()` method where the name of your filter is the `key` and the icon is the `value`:

```php
AdvancedFilter::make()
    ->filters([
        ...
    ])
    ->icons([
        'status' => 'heroicon-o-clock',
        'currency' => 'heroicon-o-currency-euro',
        'customer' => 'heroicon-o-user',
        'created_at' => 'heroicon-o-calendar',
    ])
```

### Enabling search in the Filter Picker

If the Filter Picker has a lot of available filters you can enable a search field using the ->`filterPickerSearch()` method:

```php
AdvancedFilter::make()
    ->filterPickerSearch()
```

### Configuring the number of Filter Picker columns

To change the number of columns the Filter Picker may occupy, you may use the `->filterPickerColumns()` method:

```php
AdvancedFilter::make()
    ->filterPickerColumns(2)
```

Passing an `integer` will determine how many columns are displayed at the `lg` breakpoint. You may also pass an array:

```php
AdvancedFilter::make()
    ->filterPickerColumns(['sm' => 2])
```

### Configuring the Filter Picker width

To customize the width of the Filter Picker, you may use the `->filterPickerWidth()` method, and specify a width - `xs`, `sm`, `md`, `lg`, `xl`, `2xl`, etc.

```php
AdvancedFilter::make()
    ->filterPickerWidth('md')
```

> Tip: Since the slideOver is confined to width `md`, it is recommended the Filter Picker not be set to a width larger than `md` as larger sizes will cause the slideOver to horizontally scroll. 

### Configuring the maximum height of the Filter Picker

To add a maximum height to the Filter Picker, which, in turn, allows the picker to be scrolled, you may use the `->filterPickerMaxHeight()` method, passing a CSS length:

```php
AdvancedFilter::make()
    ->filterPickerMaxHeight('240px')
```

### Hiding the filter indicator group labels

When adding multiple filter groups ("or" groups), an the Filter Group number (ie "Filter Group 1") will be prepended to the indicator to help differentiate between the different filter groups. You may disable this by passing `false` to the `->prependFilterGroupLabels()` method:

```php
 AdvancedFilter::make()
    ->prependFilterGroupLabels(false)
```

You may also hide the filter group label when there is only one filter group:

```php
 AdvancedFilter::make()
    ->prependFilterGroupLabels(prependFilterGroupLabelWhenSoleGroup: false)
```

And of course, this can be set globally in your service provider:
```php
AdvancedFilter::configureUsing(function (AdvancedFilter $filter) {
    return $filter->prependFilterGroupLabels(prependFilterGroupLabelWhenSoleGroup: false); 
}); 
```

>Tip: The name/translation of the label can be modified in the language file.

### Customizing the sequence of filter indicator group colors

When adding multiple filter groups ("or" groups), the indicators will be displayed in different colors to help differentiate between the different filter groups. By default, the indicators will be colored in the following sequence: `primary`, `info`, `gray`,  `success`, `danger`, `warning`. You may choose a different sequence by passing an array of colors to the `->indicatorColors()` method:

```php
AdvancedFilter::make()
    ->indicatorColors(['info', 'success'])
```

Any default color that is not defined in the array will be appended after the last defined color. 

### Customizing the buttons and labels

You may customize Advanced Filter Builders buttons, labels, and filter operators in the [language file](#language-files).

## Multi-Tenancy

Advanced Tables v3 has built in support for [simple one-to-many tenancy](https://filamentphp.com/docs/3.x/panels/tenancy#simple-one-to-many-tenancy), [Filament's multi-tenancy](https://filamentphp.com/docs/3.x/panels/tenancy) as well as basic support for [Spatie Multi-tenancy](https://spatie.be/docs/laravel-multitenancy/v3/introduction) and [Tenancy for Laravel](https://tenancyforlaravel.com/). (Please see [support section](#support-for-multi-tenancy) below).

Setting up tenancy with Advanced Tables will depend on your app and the tenancy implementation you are using. Please refer to the appropriate instructions for your setup: 

1. Simple one-to-many tenancy with Filament Panels - [Instructions](#setting-up-simple-tenancy-with-filament-panels)
2. Simple one-to-many tenancy with Filament's standalone Table Builder - [Instructions](#setting-up-simple-tenancy-with-filaments-standalone-table-builder)
3. Multi-tenancy with Filament Panels using Filament's tenancy implementation - [Instructions](#setting-up-multi-tenancy-with-filaments-implementation)
4. Multi-tenancy with Filament Panels using a third party tenancy implementation (Spatie/Stancl) - [Instructions](#setting-up-multi-tenancy-with-a-third-party-implementation)
5. Multi-tenancy with Filament's standalone Table Builder and a third party tenancy implementation (Spatie/Stancl) - [Instructions](#setting-up-multi-tenancy-in-filaments-standalone-table-builder-with-a-third-party-implementation)

### Simple one-to-many tenancy

Since in a [simple one-to-many tenancy](https://filamentphp.com/docs/3.x/panels/tenancy#simple-one-to-many-tenancy) implementation, each user only belongs to one tenant (*team, organization, company, etc.*), it may not be necessary to set up tenancy in Advanced Tables as each User View is already scoped to a user. However, if are allowing users to [share views](#making-a-user-view-public) or if your tenant will have admins that can create [Global Favorite Views](#enabling-making-a-user-view-a-global-favorite), you will need to enable tenancy so that each User View will be scoped to the appropriate tenant. 

#### Setting up simple tenancy with Filament Panels

1. To set up simple tenancy with Filament Panels you will need to pass your `Tenant::class` to the `->tenant()` method of the `AdvancedTablesPlugin` object:

    ```php
    AdvancedTablesPlugin::make()
        ->tenant(Team::class)
    ```

2. After you have configured your tenant model you may proceed to run the `AddTenancy` command:

    ```bash
    php artisan advanced-tables:add-tenancy
    ```

    This command will add and run the necessary migrations to finishing setting up multi-tenancy in Advanced Tables.

#### Setting up simple tenancy with Filament's standalone Table Builder

1. To set up simple tenancy with Filament's standalone Table Builder you will need to add your `Tenant::class` to your `advanced-tables.php` config file:

    ```php
    'tenancy' => [
        'tenant' => App\Models\Team::class,
    ],
    ```

2. Inside your tenant model you need to include a `getTenantId()` method so Advanced Tables knows which tenant to use for its scopes:

    ```php
    class Team extends Model
    {
        public function getTenantId(): ?string
        {
            return auth()->user()?->team_id;
        }
    }
    ```

3. After you have configured your tenant model and the `getTenantId()` method, you may proceed to run the `AddTenancy` command:

    ```bash
    php artisan advanced-tables:add-tenancy
    ```

    This command will add and run the necessary migrations to finishing setting up multi-tenancy in Advanced Tables.

### Multi-Tenancy

#### Setting up multi-tenancy with Filament's implementation

1. To set up multi-tenancy with Filament Panels and Filament's multi-tenancy implementation, first set up multi-tenancy in Filament per [Filament's instructions](https://filamentphp.com/docs/3.x/panels/tenancy).

2. After setting up tenancy in Filament, run the `AddTenancy` command:

    ```bash
    php artisan advanced-tables:add-tenancy
    ```

    This command will add and run the necessary migrations to finishing setting up multi-tenancy in Advanced Tables.

#### Setting up multi-tenancy with a third party implementation

1. To set up multi-tenancy with Filament Panels and [Spatie Multi-tenancy](https://spatie.be/docs/laravel-multitenancy/v3/introduction) or [Tenancy For Laravel](https://tenancyforlaravel.com/docs/v3/introduction) you will need to pass your `Tenant::class` to the `->tenant()` method of the `AdvancedTablesPlugin` object:

    ```php
    AdvancedTablesPlugin::make()
        // Spatie
        ->tenant(\Spatie\Multitenancy\Models\Tenant::class)
        // TenancyForLaravel
        ->tenant(\Stancl\Tenancy\Database\Models\Tenant::class)
    ```

2. After setting up tenancy, run the `AddTenancy` command:

    ```bash
    php artisan advanced-tables:add-tenancy
    ```

    This command will add and run the necessary migrations to finishing setting up multi-tenancy in Advanced Tables.

#### Setting up multi-tenancy in Filament's standalone Table Builder with a third party implementation

1. To set up multi-tenancy with Filament's standalone Table Builder along with [Spatie Multi-tenancy](https://spatie.be/docs/laravel-multitenancy/v3/introduction) or [Tenancy For Laravel](https://tenancyforlaravel.com/docs/v3/introduction) you will need to add your `Tenant::class` to your `advanced-tables.php` config file:

    ```php
    'tenancy' => [
        'tenant' => \Spatie\Multitenancy\Models\Tenant::class,
    ],
    ```

2. After you have configured your tenant model, you may proceed to run the `AddTenancy` command:

    ```bash
    php artisan advanced-tables:add-tenancy
    ```

    This command will add and run the necessary migrations to finishing setting up multi-tenancy in Advanced Tables.

### Configuring the table column

If you had previously manually implemented multi-tenancy in Advanced Tables and need to reference a table column other than the default `tenant_id`, you may configure it by passing your column name to the `->tenantColumn()` method:

```php
AdvancedTablesPlugin::make()
    ->tenantColumn('account_id')
```

### Ignoring multi-tenancy

If you are using multi-tenancy in your app, but would prefer User Views and Preset Views to *not* be scoped to each tenant (i.e. a user's views would be the same regardless of which tenant they are in), you may ignore multi-tenancy in the plugin by passing `false` to the `->scopeToTenancy()` method:

```php
AdvancedTablesPlugin::make()
    ->scopeToTenancy(false)
```

### Support for multi-tenancy

Advanced Tables only fully supports Filament's official multi-tenancy implementation. Since third-party multi-tenancy implementations with either Spatie or Tenancy for Laravel can vary dramatically from developer to developer, it is possible that Advanced Tables will not be fully compatible. Please be sure you have multi-tenancy fully working and tested before attempting to implement multi-tenancy in Advanced Tables. Support can only be provided for issues pertaining to Advanced Tables.

## User Views Resource

Starting in v3, the User Views Resource is a Filament table resource primarily for admins to be able to manage the User Views of *all* their users. It is also where admins can approve or reject User Views with the [approval system](#approving-public-and-global-favorite-user-views-new).

> Important: You will need to set up a [policy](#authorization) to limit access to the User Views Resource. Without a policy, any user will be able to rename, update, or delete any User View. See the policy section for more information.

### Easily toggling a views public, or global setting

The icons in the rows are actionable and can be clicked to quickly toggle the setting. 

### User Views Resource configurations

Advanced Tables offers multiple ways to customize the User Views Resource. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`.

#### Disabling the User Views Resource

Advanced Tables enables the User Views Resource by default. If you are not using User Views, you may disable this by passing `false` to the `resourceEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->resourceEnabled(false)
```

If you wish to just limit access to the User Views Resource, you should create a [policy](#authorization).

#### Customizing the labels

You may customize the `model label`, `plural model label`, and `navigation label` in the [language file](#language-files).

#### Customizing the navigation icon

You may customize the [navigation icon](https://filamentphp.com/docs/3.x/panels/navigation#customizing-a-navigation-items-icon) by passing a `heroicon` to the `resourceNavigationIcon()` method:

```php
AdvancedTablesPlugin::make()
    ->resourceNavigationIcon('heroicon-o-star')
```

#### Customizing the navigation group

You may customize the [navigation group](https://filamentphp.com/docs/3.x/panels/navigation#grouping-navigation-items) by passing a `string` to the `resourceNavigationGroup()` method:

```php
AdvancedTablesPlugin::make()
    ->resourceNavigationGroup('Settings')
```

#### Customizing the navigation sort order

You may customize the [navigation sort order](https://filamentphp.com/docs/3.x/panels/navigation#sorting-navigation-items) by passing an `int` to the `resourceNavigationSort()` method:

```php
AdvancedTablesPlugin::make()
    ->resourceNavigationSort(1)
```

#### Disabling the Navigation Badge

By default, Advanced Tables shows a badge in the navigation of the number of unapproved views. You may disable this by passing `false` to the `resourceNavigationBadge()` method:

```php
AdvancedTablesPlugin::make()
    ->resourceNavigationBadge(false)
```

#### Disabling loading all users in the user select filter

By default, when filtering users in the User Views Resource all users will be loaded. This is fine for smaller applications with a handful of users, but if you application has hundreds or thousands of users, you may disable loading all users by passing `false` to the `resourceLoadAllUsers` method:

```php
AdvancedTablesPlugin::make()
    ->resourceLoadAllUsers(false)
```

#### Using multiple panels

When using [multiple panels](https://filamentphp.com/docs/3.x/panels/configuration#overview) the User Views Resource by default will only show the User Views associated with the current panel's resources. However, since the `UserViewResource::class` is part of the plugin, if you create views *on* the User View Resource then those views will appear in every panel's User Views Resource. Sometimes, this maybe desired. For example, if you create an "Approved" view on the User View Resource, you may want that view to appear in the User Views Resource of every panel. 

However, if you prefer each User Views Resource to be independent, you can follow the steps below:

> Note: This will only affect future views created for the User Views Resource. It will not update views you previously created for your User Views Resource.

1. Copy `archilex/filament-filter-sets/src/Resources/UserViewResource.php` and `archilex/filament-filter-sets/src/Resources/UserViewResource/Pages/ManageUserViews.php` files to your panels directory:

    ```
    +-- Filament
    │   +-- SecondaryPanel
    │   │   +-- Resources
    │   │   │   +-- UserViewResource.php
    │   │   │   +-- UserViewResource
    │   │   │   │   +-- Pages
    │   │   │   │   │   +-- ManageUserViews.php
    ```

    > Note: While you can extend the plugin's UserViewResource for each panel, it is also possible to use the plugin's UserViewResource for your main panel and only extend the resource for your secondary panels.

2. Extend UserViewResource.php:

    ```php
    namespace App\Filament\SecondaryPanel\Resources;

    use App\Filament\SecondaryPanel\Resources\UserViewResource\Pages\ManageUserViews;
    use Archilex\AdvancedTables\Resources\UserViewResource as Resource;

    class UserViewResource extends Resource
    {
        public static function getPages(): array
        {
            return [
                'index' => ManageUserViews::route('/'),
            ];
        }
    }
    ```

3. Update ManageUserViews.php

    ```php
    namespace App\Filament\SecondaryPanel\Resources\UserViewResource\Pages;

    use App\Filament\SecondaryPanel\Resources\UserViewResource;
    use Archilex\AdvancedTables\AdvancedTables;
    use Filament\Resources\Pages\ManageRecords;

    class ManageUserViews extends ManageRecords
    {
        use AdvancedTables;

        protected static string $resource = UserViewResource::class;
    }
    ```

Now, when you create a view inside that panel's User Views Resource it will only appear in that panels' User Views Resource.

##### Showing user views from multiple panels

As mentioned, by default the User Views Resource will only show the User Views that are associated to that panel. However, if you would like to include views from other panels you can do that by passing an array of panel ids to the `->resourcePanels()` method.

```php
AdvancedTablesPlugin::make()
    ->resourcePanels(['admin', 'secondaryPanel'])
```

> Note: The `open` action will only be displayed for the current panel's user views.

## Authorization

Depending on your application, you may not want to give all of your users the ability to use all the functions. Here are a few example situations:

- You want to limit access to the User Views Resource to only administrators.
- You only want the administrator to be able to create global favorite User Views.
- You want your users to be able to create their own User Views, but not make them globally or publicly available to other users.
- You want to disallow picking colors for User Views.

Advanced Tables handles authorization with [Laravel policies](https://laravel.com/docs/10.x/authorization). Beyond Filament's normal [policy methods](https://filamentphp.com/docs/3.x/panels/resources/getting-started#authorization), Advanced Tables includes the following additional methods:

### Policy Methods
`makePublic()` is used to control who can make a User View publicly available to the other users.
`makeFavorite()` is used to control who can add a User View to their favorites. Usually this will be enabled for all users.
`makeGlobalFavorite()` is used to control who can make a User View a global favorite for all users. Usually this would only be administrators.
`selectIcon()` is used to control if you want to allow your users to select an icon for a User View.
`selectColor()` is used to control if you want to allow your users to select colors for a User View.

#### Policy example

To make setting up these policies easy Advanced Tables includes a sample `UserViewPolicy`. To implement this policy, first create your own policy:

```bash
php artisan make:policy UserViewPolicy
```

Next, locate the newly created `UserViewPolicy` and replace its contents with the contents in the example `UserViewPolicy` located in this plugin's `Policies` directory.

Finally, even though Laravel may automatically detect your policy, it is recommended you explicitly register it in `App\Providers\AuthServiceProvider`:

```php
use App\Policies\UserViewPolicy;
use Archilex\AdvancedTables\Models\UserView;

protected $policies = [
    UserView::class => UserViewPolicy::class,
];
```

#### Example policy assumptions

The example policy assumes:

1. You are using the default `User::class` and that it's located in the `App\Models\` directory as has been the default since Laravel 8.
2. You have an `isAdmin()` method on your user model.

#### Policies applied by example 

The example policy will apply the following policies: 

1. Only admins will be able to view the User Views Resource.
2. All users can create User Views.
3. Only admins or the owner of the User View can view, update, or delete their User View.
4. Only admins can bulk delete User Views.
5. All users can make their User Views public.
6. All users can favorite their User Views or other user's User Views.
7. Only admins can make a User View a global favorite.
8. All users can select an icon for their User Views.
9. All users can select a color for their User Views.

## Additional Configurations

### Table Loading Indicators (New)

If you would like to give your users more feedback when their table is loading, you may enable a loading skeleton overlay by adding the `->tableLoadingOverlay()` method:

```php
AdvancedTablesPlugin::make()
    ->tableLoadingOverlay()
```

If any of your table columns are using the `->extraCellAttributes()` method, you will need to make sure you pass in `true` as the second parameter so that your attributes are merged with the plugin's:

```php
TextColumn::make('name')
    ->extraCellAttributes([
        'class' => 'bg-gray-500'
    ], merge: true)
```

Additional loading indicator types and effects will be coming in the future. Feel free to reach out to me with your suggestions.

> Note: Be sure to run `npm run build` and `php artisan filament:upgrade` after enabling this feature.

### User::class

If you are using a User configuration other than Laravel's default, you should configure these *before* running your migrations:

#### Configuring the User::class

You may customize the `User::class` by passing your custom class to the `user()` method:

```php
AdvancedTablesPlugin::make()
    ->user(MyUser::class)
```

#### Configuring the users database table

You may customize the users database table by passing the name of your table to the `userTable()` method:

```php
AdvancedTablesPlugin::make()
    ->userTable('my_users_table')
```

#### Configuring the user name columns

By default, Laravel's default `users` table includes a `name` column which Advanced Tables expects to exist. If you have modified your `users` table to something such as `first_name` and `last_name` you may configure this using the `userTableNameColumn()` method:

```php
AdvancedTablesPlugin::make()
    ->userTableNameColumn('first_name')
```

If you have only have a `first_name` and `last_name` column, but still wish to show a user's full name in the User Views Resource, you may create a virtual column to support this:

```php
$table->string('full_name')->virtualAs('concat(first_name, \' \', last_name)');
```

```php
AdvancedTablesPlugin::make()
    ->userTableNameColumn('full_name')
```

#### Configuring the user primary key

If you are set your primary key on your `User::class` model to something other than Laravel's default `id`, you should also configure this in Advanced Tables using the `userTableKeyColumn()` method:

```php
AdvancedTablesPlugin::make()
    ->userTableKeyColumn('uuid')
```

#### Configuring the authentication guard

By default, Advanced Tables will use whichever authentication guard is [set on your Filament panel](https://filamentphp.com/docs/3.x/panels/users#setting-the-authentication-guard). If you are using standalone Table Builder, you may set the authentication guard in the `advanced-tables` config file:

```php
'users' => [
    'auth_guard' => 'web',
],
```

### Language Files

Each text field in Advanced Tables has been added to the language file allowing you to customize the text to better fit your application needs. You can publish the language files with:

```bash
php artisan vendor:publish --tag=advanced-tables-translations
```

This will copy the language files to your `resources\lang\vendor\advanced-tables` directory. Currently 🇺🇸 English, 🇲🇽 Spanish, and 🇫🇷 French translations are available.


## Filament Table Builder

Advanced Tables has full support for [Filament's Table Builder](https://filamentphp.com/docs/3.x/tables/installation). 

Before proceeding, please refer to the [setup instructions](#setting-up-advanced-tables-in-filament-table-builder).
### Getting started

#### Adding the Advanced Tables trait

To use Advanced Tables, you need to add the `AdvancedTables` trait to your component. However, as Advanced Tables overrides multiple methods in Filament's `InteractsWithTables` trait, adding the `AdvancedTables` trait to the table will cause a conflict. 

For convenience, Advanced Tables includes a `Page` class which you can use to quickly get up and running:

```php
use Archilex\AdvancedTables\AdvancedTables;
use Archilex\AdvancedTables\Livewire\Page;

class ListUsers extends Page
{
    use AdvancedTables;

    ...
```

Of course, there are multiple ways to prevent the trait conflict. The important part is to ensure that the `AdvancedTables` trait is used on a class that extends another class which contains Filament's `InteractsWithTables` trait.

#### Adding the view component to your blade file

You also need to add the Favorites Bar component to your blade file:

```html
<div class="space-y-6">
    
    <x-advanced-tables::favorites-bar />

    {{ $this->table }}
</div>
```

The Favorites Bar expects a space of `24px` to properly display it's links. This can easily be achieved with Tailwind's `space-y-6` class as shown above.

### Managing User Views

If you are using the Filament Panels, Advanced Tables comes with a `UserViewResource` so admins can manage all of their user's views. If you are using Filament Tables, you can recreate this table:

1. Create a new Livewire component

    ```bash
    php artisan make:livewire ListUserViews
    ```

2. Locate the `ListUserViews.php` file in this plugins `Livewire` directory and copy and paste its contents into your newly created `ListFilterSets` component.

3. Add the Favorites Bar to your `list-user-views` view component:

    ```html
    <div class="space-y-6">
        
        <x-advanced-tables::favorites-bar />

        {{ $this->table }}
    </div>
    ```

4. Finally add the route to `routes/web.php`.
    
    ```php
    Route::get('/user-views', App\Livewire\ListUserViews::class)->middleware(['auth', 'verified']);
    ```

### Configurations

All of the configurations listed above are also available when using Filament's standalone Table Builder. However, these will need to be configured in the config file. 

## Tips and Tricks

### Create and export reports

By combining Advanced Tables with the powerful [Excel Export](https://filamentphp.com/plugins/pxlrbt-excel) by Dennis Koch, you and your users can take full advantage of your custom views to generate customizable reports. Your view's filters, toggled columns, sorting, and reordered columns are automatically configured in your exported data. Advanced Tables and Excel Export make customizing, saving, and exporting reports easy, yet powerful.

1. Install Excel Export per the plugins [instructions](https://filamentphp.com/plugins/pxlrbt-excel#installation)
2. Add the `ExportBulkAction` to your table:

```php
public static function table(Table $table): Table
{
    return $table
        ->bulkActions([
            ExportBulkAction::make()
        ]);
}
```

3. Create your custom view using either [Preset Views](#preset-views) or [User Views](#user-views). Use whichever combination of filters, sorting, and toggled columns you like. Remember, with Advanced Tables you can also [reorder your columns](#reorderable-columns-new) as well!

4. [Save your custom view](#quick-save-new). If this will be a report you generate frequently, you can add it to your [Favorites Bar](#favorites-bar). Or just keep it in the [View Manager](#view-manager-new) for easy access later on.

5. Click the `bulk select` button in the table header to select the records in your custom view and then choose `Export`. Your selected records will be downloaded, sorted, filtered, and organized, just like you want. 

Be sure to check out the rest of [Excel Export's docs](https://filamentphp.com/plugins/pxlrbt-excel) for further ways to customize your exports. And if Excel Export is helpful to your business, be sure to [sponsor Dennis](https://github.com/sponsors/pxlrbt).

### Updating your Widgets or Charts automatically

Filament v3 now makes it easy for you to have your widgets and charts automatically update when you filter your views using Advanced Tables. Now, when you choose one of your Views, your widgets and/or charts will update to reflect your filtered data. 

> Note: While you can use [Filament's](https://filamentphp.com/docs/3.x/panels/resources/widgets#accessing-page-table-data-in-the-widget) `ExposesTableToWidgets` and `InteractsWithPageTable` traits, if you are using Preset View's `->modifyQueryUsing()` method you *must* use Advanced Table's versions to fully support interactivity on the first click.

1. Add the `ExposesTableToWidgets` trait to your page class:

```php 
use Archilex\AdvancedTables\Widgets\Concerns\ExposesTableToWidgets;

class ListOrders extends ListRecords
{
    use ExposesTableToWidgets;
}
```

2. Inside your widget classes, add the `InteractsWithPageTable` trait and return the name of the page class from the `getTablePage()` method:

```php 
use Archilex\AdvancedTables\Widgets\Concerns\InteractsWithPageTable;

class OrderStats extends Widget
{
    use InteractsWithPageTable;
 
    protected function getTablePage(): string
    {
        return ListOrders::class;
    }
}
```

3. Finally, in your widget class, use the `$this->getPageTableQuery()` to access the query builder instance:

```php
use Filament\Widgets\StatsOverviewWidget\Stat;

Stat::make('Orders', $this->getPageTableQuery()->count()),
```

That's it! Now when you click on one of your Views, the widgets will update accordingly. See [Filament's docs](https://filamentphp.com/docs/3.x/panels/resources/widgets#accessing-page-table-data-in-the-widget) for more details.

## Support

Question? Bug? Feature request? Comment or suggestion? Email me at advancedtables@gmail.com or join us on [#advanced-tables on Discord]( https://discord.com/channels/883083792112300104/1093480983988281394). I'd love to hear from you.

## Changelog

Please see [CHANGELOG](https://changelog.anystack.sh/filament-filter-sets) for more information on what has changed recently.

## Contributing

Users with active licenses may access the private repo to contribute by visiting the `Licenses` tab of your AnyStack account. 

## Credits

- [Kenneth Sese](https://github.com/archilex)

## License

### Single License
The Single License grants the Licensee permission to use Advanced Tables in a single project hosted on a single domain or subdomain. Examples include a personal website or a website for a single client.

If you would like to implement Advanced Tables in a SaaS application, you will need an [Unlimited](#unlimited-license) or [Lifetime license](#lifetime-license).

The single license grants permission for up to 5 Employees and Contractors (i.e. developers) of the Licensee to access and use Advanced Tables.

You will receive updates and bug fixes for one year from the date of purchase. Should you decide not to renew your license, you will only be able to install the package up to the last version available before the license expired. You can renew the license at a discounted price to continue receiving updates and new features.

### Unlimited License
The Unlimited License grants the Licensee permission to use Advanced Tables on **unlimited** domains and subdomains, including SaaS applications. 

The unlimited license grants permission for up to 25 Employees and Contractors (i.e. developers) of the Licensee to access and use Advanced Tables. There is no limit on the amount of end-users your app may have.

You will receive updates and bug fixes for one year from the date of purchase. Should you decide not to renew your license, you will only be able to install the package up to the last version available before the license expired. You can renew the license at a discounted price to continue receiving updates and new features.

### Lifetime License
The Lifetime License grants the Licensee permission the same benefits as the Unlimited License.

You will receive updates for the lifetime of the product. 

The unlimited license grants permission for up to 25 Employees and Contractors (i.e. developers) of the Licensee to access and use Advanced Tables. There is no limit on the amount of end-users your app may have.

### Code Distribution
None of Advanced Tables' licenses allow the public distribution of its source code. So, you may not build an application using Advanced Tables and distribute that application publicly via an open source repository, hosting platforms, or any other code distribution platform.

### Questions?
Unsure which license you need? Email me at advancedtables@gmail.com with your questions.
