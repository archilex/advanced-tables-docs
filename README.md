# Advanced Tables (formerly Filter Sets)

![Advanced Tables with View Manager](https://user-images.githubusercontent.com/6097099/269182900-f3226af9-8e0c-4895-98e6-58499a76de7f.png)

## Introduction

Advanced Tables (formerly known as Filter Sets) is a premium plugin for [Filament](https://filamentphp.com/) that supercharges your tables with powerful features like user customizable views, enhanced filter tabs, reorderable columns, convenient view management, and more. 

At its core, Advanced Tables allows you to combine filters, grouping, toggled columns, and more into custom views that are just one click away. Users no longer have to rebuild their views each time they need to focus on a certain subset of their data. Advanced Tables gives your users fast access to the information they need.

With Advanced Tables, views can be set up in advance by the developer or they can be created on-the-fly by your end-users using Quick Save. And with Advanced Table’s View Manager, your users will be able to conveniently create, apply, edit, share, and sort their views right from the resource or table.

Best of all, Advanced Tables works with *all* of your Filament tables including Resource Tables, Relation Managers, Table Widgets, and standalone Table Builder.

### Video

Check out a short video of some of the powerful features included in Advanced Tables
[![Youtube video](https://user-images.githubusercontent.com/6097099/269337282-39ae1c24-eb4c-4d0b-9c88-11fcf14297ef.png)](https://www.youtube.com/watch?v=_vhVHiBzqrs)

### Features

- Allow your users to save their filters, toggled columns, grouping, and more in customizable [User Views](#user-views)
- Developers can create [Preset Views](#preset-views) in code and deploy them for their clients
- (New) Preset Views can also include [filters](#applying-filters-new), [grouping](#applying-default-grouping-new), [toggled columns](#toggling-and-reordering-columns-new), and [column order](#toggling-and-reordering-columns-new)
- (New) The [Quick Save](#quick-save-new) button means saving custom views is just one click away
- (New) Enhance your tables with [Column Reordering](#reordering-columns)
- Easily access views in the [Favorites Bar](#favorites-bar)
- (New) Sort, favorite, and edit views on the table using the [View Manager](#view-manager-new)
- (New) [SlideOver](#displaying-as-a-slideover), [modal](#displaying-as-a-modal), and dropdown options
- Choose from six different [themes](#themes)
- Includes a [User Views Resource](#user-views-resource) so your admins can manage all user views
- Users can make their User Views [publicly](#making-a-user-view-public) available to all users
- Admins can create [global favorite views](#making-a-user-view-public) that will appear for all users
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

Advanced Tables requires `PHP 8.1+`, `MySQL 5.7.8+` or `Postgres`, and `Filament 3.0+`.

*Advanced Tables v1 is fully compatible with `Filament v2`. After purchasing a license here, please refer to the [Filter Sets v1](https://v2.filamentphp.com/plugins/filter-sets) documentation for installation and usage instructions.*

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

*Important: Advanced Tables was formerly named Filament Filter Sets, but for compatibility with previous versions, the repository has maintained its original name.*

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

*Tip: If you get a `402 error`, most likely you forgot to add the colon and fingerprint.*

### Setting up Advanced Tables in Filament Panels (including Relation Managers and Table Widgets)

*If using Filament's standalone Table Builder, please refer to the [Filament Table Builder setup instructions](#setting-up-advanced-tables-in-filament-table-builder)*

1. Publish and run the migrations
    *Important: If you are using a User class other than Laravel's default `User::class` or a user's table other than Laravel's default `users` you should [update these configurations](#configuring-the-userclass) **before** migrating.*

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
    use Archilex\AdvancedTables\AdvancedTablesPlugin;
    
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

### Setting up Advanced Tables in Filament Table Builder

*If using Filament Panels, please refer to the [Filament Panels setup instructions](#setting-up-advanced-tables-in-filament-panels-including-relation-managers-and-table-widgets)*

*Important: Beyond the [normal requirements](#requirements), using Advanced Tables with Filament Table Builder requires you have some type of user authentication system such as [Laravel Breeze](https://laravel.com/docs/10.x/starter-kits#laravel-breeze) since each view belongs to the currently authenticated user.*

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
    php artisan vendor:publish --tag="filament-filter-sets-migrations"
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

### Deploying

When deploying, it is not advised to store your `auth.json`` file inside your project's version control repository. To store your credentials on your deployment server you may create a [Composer auth.json file](https://getcomposer.org/doc/articles/http-basic-authentication.md) in your project directory using the following command: 

```bash
composer config http-basic.filament-filter-sets.composer.sh your_account_email your_license_key_including_your_fingerprint_domain
```

*Important: Don't forget to append your fingerprint domain to your password.*

You can see your credentials in your [Anystack account](https://account.anystack.sh/transactions): `Anystack > Transactions > View details` next to Filament Filter Sets. 

*Tip: Make sure the `auth.json` file is in `.gitignore` to avoid leaking credentials into your git history.*

If you are using Laravel Forge, you don't need to create the `auth.json` file manually. Instead, you can set the credentials on the `Composer Package Authentication` screen of your server. 

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
- Two new [themes](#themes) (Github and Filament)
- Easily add colors to the color picker using Filament's `Color::class`
- More than 60 configuration options to completely customize Advanced Tables to your needs

### Upgrading

Advanced Tables is almost a complete rewrite of previous releases and thus requires numerous changes to completely upgrade. I've tried to document every required change, but if you have issues or if I have missed a step, please reach out to me at advancedtables@gmail.com.

#### Before you begin

Before you begin, be sure to follow the setup instructions for [Filament panels](#setting-up-advanced-tables-in-filament-panels-including-relation-managers-and-table-widgets) or [Table Builder](#setting-up-advanced-tables-in-filament-table-builder).

#### High-impact changes

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

*Important: Previously, you would only need to use the `HasFavorites` trait if you wanted to use the Favorites Bar on a table. As of v3, the `AdvancedTables` trait is the main entry point for the plugin. This means that anywhere you were using `FilterSetFilter` without the respective `HasFavorite` trait you will now need to add the `AdvancedTables` trait to the appropriate class, usually `List*` or `Manage*`.*

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

*The helper service exists to get you up and running as quickly as possible. However, when convenient, it's recommended you implement your own script to update the icons directly in your database and then disable this helper.*

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

*Important: Be sure that any column included in `defaultColumns` is present in on the `columns` method of your table.*

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

*Note: If you are using the standalone Table Builder the configurations are handled in the new `advanced-tables.php` [config file].*

#### What's next

Now that you've successfully upgraded, be sure to take a look at all the [new features](#new-features) for additional options.

## Getting started

### Adding Advanced Tables to your table

To use Advanced Tables you will need to add the `AdvancedTables` trait to the appropriate class depending on whether you intend to use it on a [Resource Table](#resource-tables), [Simple Resource Table](#simple-modal-resource-tables), or [Table Widget](#table-widgets).

*Important: For standalone Table Builder users, please refer to the documentation for [using Advanced Tables with Table Builder](#filament-table-builder)*

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

To change a User View's table configuration of filters, columns, grouping, etc. you must overwrite the existing view:

1. Set the table up with the desired configuration.
2. Click the `+` in the top right corner of the table.
3. Name the view the *same* name as the view you want to overwrite
4. Apply any of the favorite, public, and/or global settings.
5. Save the view.

Saving a view with the same name will overwrite the existing view, updating the table configuration for that view.

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

*Important: Since icons are cached, after updating you will need to clear your cache to see the change with `php artisan cache:clear`*

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

*Tip: If you want to display multiple badges, you should generate one query separately and then use [Laravel collections](https://laravel.com/docs/10.x/collections#main-content) to filter and count them.*

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

*Tip: If your policy is not working, be sure to register it in `AuthServiceProvider` as sometimes Laravel does not successfully auto-register policies.*

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

*Tip: To see how the table filter array is created, you can `dd($this->tableFilters)` in your table.*

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

*Tip: While it is possible to add `orderBy()` to your query to sort your table, using `defaultSort()` is recommended as it will correctly show the sorting indicator on the table column.*

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

*Note: By preserving a user's selection you are in turn removing the option for a Preset View to always take a user to that view's predefined configuration as that view is now affected by the user.*

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
AdvancedTablesPlugin::make()
    ->favoritesBarTheme('filament')
```

*Note: Since `links-simple` only has color to visually distinguish between active and in-active states, it is recommended you [disable the ability to select a color](#disabling-the-color-picker) for their User Views since it becomes difficult to know which link is active.*

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

*Note: In prior versions this view was named `All`, however when clicking this view, it actually resets the table to it's ***default*** settings, which may or may not contain all the records. For this reason, it was renamed to `default` in version 3. However, you may change the name of the Default View in the [language file](#language-files).*

*Tip: If you need an `All` button in addition/instead of a `Default` button, you can easily create a [Preset View](#creating-a-preset-view) that shows the data you need.*

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

## Quick Save (New)

Advanced Tables offers a quick way for end-users to save User Views with the Quick Save button. Quick Save can be customized in a variety of ways to match the needs of your application.

### Quick Save configurations

Advanced Tables offers multiple ways to customize Quick Save. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`.

#### Disable Quick Save

You may disable User Views entirely which will also remove the Quick Save button by passing `false` to the `userViewsEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->userViewsEnabled(false)
```

However, by disabling User Views, you also disable public and global favorite User Views. If you wish to just hide the Quick Save button for certain users, you should use [policies](#authorization).

#### Changing the icon

You may change the icon of the Quick Save button using the `icon` argument of the `quickSaveInFavoritesBar()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(icon: 'heroicon-o-bookmark')
```

*Note: The Quick Save icon only applies when the button is in the Favorites Bar.*

#### Changing the position in the Favorites Bar

By default, Quick Save is at the end of the Favorites Bar. You may position it at the start of the Favorites Bar using the `quickSaveInFavoritesBar()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(position: 'start')
```

#### Displaying in the table toolbar

By default, Quick Save is displayed in the Favorites Bar. You may display it in the toolbar next to the Filters dropdown by passing `false` to the `quickSaveInFavoritesBar()` method:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(false)
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
3. Prest views (non-favorited Preset Views)
3. Public views (other user's public views)
4. Global views (global favorites that have been removed from the user's favorites)

#### Action button

Next to each view is an action button that gives the user several options depending on the type of view:

1. Apply view
2. Add to favorites/Remove from favorites
3. Edit view (only displayed for the User Views created by the user)
4. Delete view (only displayed for the User Views created by the user)

#### Sorting views

User favorites, User views, and Preset views can be sorted by clicking the up/down arrows and then dragging/dropping the view to the desired location. Each view will be confined to it's section. 

*Important: If the User Favorites section contains both Preset Views and User Views, Preset Views will always come first, followed by User Views. These two types of views can only be sorted within their respective groupings. In other words, Preset Views can only be sorted among other Preset Views, and User Views can only be sorted among other User Views.*

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

#### Disable View Manager

You may disable the View Manager entirely which will also remove the View Manager button by setting both `viewManagerInFavorites()` and `viewManagerInTable()` to `false` and displaying the View Manager as a slideOver. This hides the View Manager from the table and also ensures that only the user's favorites are [queried from the database](#dropdown-vs-slideover-internally). 

```php
AdvancedTablesPlugin::make()
    ->viewManagerInFavoritesBar(false)
    ->viewManagerInTable(false)
    ->viewManagerSlideOver()
```

#### Changing the icon

You may change the icon used for the View Manager using the `viewManagerIcon()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerIcon('heroicon-o-bars-3')
```

#### Hiding the active view badge indicator

When displaying the View Manager as a dropdown, by default a badge indicator will be shown when there is an active View. You may disable the badge by passing `false` to the `viewManagerBadge()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerBadge(false)
```

*Note: The active view badge indicator is only available when the View Manager is used as a dropdown.*

#### Hiding the search field

By default the View Manager includes a search field to quickly search for views. You may disable the search field by passing `false` to the `viewManagerSearch()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerSearch(false)
```

#### Displaying a Save View link

You may include a Save View link inside the View Manager with the `viewManagerquickSave()` method:

```php
AdvancedTablesPlugin::make()
    ->viewManagerquickSave()
```

This also allows you to hide the Quick Save button from the Favorites Bar to maximize the space available in the Favorites Bar:

```php
AdvancedTablesPlugin::make()
    ->quickSaveInFavoritesBar(false)
    ->viewManagerInFavoritesBar(false)
    ->viewManagerInTable()
    ->viewManagerquickSave()
```

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

## Reorderable Columns (New)

Advanced Tables enhances Filament's [toggleable columns](https://filamentphp.com/docs/3.x/tables/columns/getting-started#toggling-column-visibility) dropdown with powerful column reordering. Now you and your users can move hide, show, and move columns to create a totally custom view. Best of all, when a user creates a new User View, their new column order is saved as well. 

### Reordering columns

To reorder columns:

1. Click the toggle column button in the table toolbar to open the column dropdown. 
2. Click the `up/down arrow` button to enable reordering
3. Drag and drop your columns in the order you prefer.

*Note: At least one column in your table must be `toggleable()` for Filament to display the toggle column button.*

### Reorderable Columns configurations

Advanced Tables offers multiple ways to customize Reorderable Columns. Unless specified otherwise, these options can be configured directly on the `AdvancedTablesPlugin` object inside your `PanelProvider`. 

#### Disabling column reordering

Advanced Tables enables column reordering by default. You may disable this and use Filament's native column toggling UI by passing `false` to the `reorderableColumnsEnabled()` method:

```php
AdvancedTablesPlugin::make()
    ->reorderableColumnsEnabled(false)
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

## User Views Resource

Starting in v3, the User Views Resource is a Filament table resource primarily for admins to be able to manage the User Views of *all* their users. It is also where admins can approve or reject User Views with the [approval system](#approving-public-and-global-favorite-user-views-new).

*Important: You will need to set up a [policy](#authorization) to limit access to the User Views Resource. Without a policy, any user will be able to rename, update, or delete any User View. See the policy section for more information.*

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

### Language Files

Each text field in Advanced Tables has been added to the language file allowing you to customize the text to better fit your application needs. You can publish the language files with:

```bash
php artisan vendor:publish --tag=filament-filter-sets-translations
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

## Support

Question? Bug? Feature request? Comment or suggestion? Email me at advancedtables@gmail.com or join us on [#advanced-tables on Discord]( https://discord.com/channels/883083792112300104/1093480983988281394). I'd love to hear from you.

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Kenneth Sese](https://github.com/archilex)
- [All Contributors](../../contributors)

## License

### Single License
The Single License grants the Licensee permission to use Advanced Tables in a single project hosted on a single domain or subdomain. Examples include a personal website or a website for a single client.

If you would like to implement Advanced Tables in a SaaS application, you will need an unlimited license.

The single license grants permission for up to 5 Employees and Contractors of the Licensee to access and use Advanced Tables.

### Unlimited License
The Unlimited License grants the Licensee permission to use Advanced Tables on **unlimited** domains and subdomains, including SaaS applications. 

The unlimited license grants permission for up to 25 Employees and Contractors of the Licensee to access and use Advanced Tables.

### Code Distribution
None of Advanced Tables' licenses allow the public distribution of its source code. So, you may not build an application using Advanced Tables and distribute that application publicly via an open source repository, hosting platforms, or any other code distribution platform.

### Questions?
Unsure which license you need? Email me at advancedtables@gmail.com with your questions.
