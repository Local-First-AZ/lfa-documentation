---
sidebar_position: 1
---

# Menu Sections

Menu items in the Vitality template use Markdown language which is a simpler version of HTML. The template comes with menu sections already built in with sample menu items.

To add a pre-built menu section, click `Add Section > Saved sections` and choose a template from the list. This will add the section to your website.

![Image7](/screenshots/image7.png)

To edit the menu items, click on it and select `Edit`.

![Image12](/screenshots/image12.png)

Alternatively, you can create a blank section. In the editor, choose `Add Block > Markdown` and add the menu items yourself by copying the code snippets found in this documentation.

<img src="/screenshots/image13.png" width="200" height="auto" />
<img src="/screenshots/image5.png" width="210" height="auto" />

## Editing and creating menu items

:::tip
Code can be copied by clicking on the copy icon at the top right corner of the code block
:::

Markdown code for a single menu item:

```jsx
##### <span class="menu-item__title">Green Goddess Smoothie</span>

<div class="menu-item__d_p">
  <span class="menu-item__description">
    A refreshing blend of spinach, kale, banana, pineapple, and coconut water,
    packed with vitamins and antioxidants.
  </span>
  <span class="menu-item__price">$7.99</span>
</div>
```

To add a separator line, add `- - -` underneath the code block. For example:

```jsx
##### <span class="menu-item__title">Green Goddess Smoothie</span>

<div class="menu-item__d_p">
  <span class="menu-item__description">
    A refreshing blend of spinach, kale, banana, pineapple, and coconut water,
    packed with vitamins and antioxidants.
  </span>
  <span class="menu-item__price">$7.99</span>
</div>
// highlight-next-line
---
```

:::warning
Please make sure to only replace the text in **red**. Replacing or deleting other parts of the code will result in errors.
:::

### Adding multiple menu items

Here is an example of a 3 item menu:

```jsx
##### <span class="menu-item__title">Green Goddess Smoothie</span>

<div class="menu-item__d_p">
  <span class="menu-item__description">
    A refreshing blend of spinach, kale, banana, pineapple, and coconut water,
    packed with vitamins and antioxidants.
  </span>
  <span class="menu-item__price">$7.99</span>
</div>

---

##### <span class="menu-item__title">Berry Blast Acai Bowl</span>

<div class="menu-item__d_p">
  <span class="menu-item__description">
    A thick and creamy blend of acai berries, mixed berries, banana, and almond
    milk topped with granola, fresh berries, sliced banana, and a drizzle of
    honey.
  </span>
  <span class="menu-item__price">$9.99</span>
</div>

---

##### <span class="menu-item__title">Cucumber Mint Infused Water</span>

<div class="menu-item__d_p">
  <span class="menu-item__description">
    Cool and refreshing water infused with slices of cucumber and fresh mint
    leaves, the perfect hydrating beverage.
  </span>
  <span class="menu-item__price">$2.99</span>
</div>
```

If you want to try and add other elements, here is a [link](https://support.squarespace.com/hc/en-us/articles/206543587-Markdown-cheat-sheet?_ga=2.177167525.1412756233.1709854110-1867369668.1705272037&platform=v6&websiteId=65e4c94e32ba2d342870577b) to the markdown cheatsheet.

:::warning
Please note that this is an advanced feature so please try it at your own risk. If you want to revert back to the original version, you can copy the code from this document.
:::

## Adding dietary restrictions to menu sections

Allergen tables can be used in the code block or the Markdown block. `Add Block > Code` or `Add Block > Markdown`.

<img src="/screenshots/image5.png" width="250" height="auto" />

Copy the below code, paste it in the code or markdown block where needed and change the attribute values based on your requirements

```jsx
<div class="dietary_restrictions" data-icon-size="40" data-align="left">
  <span class="gluten-free">Gluten Free</span>
  <span class="no-added-sugar">No Added Sugar</span>
  <span class="vegan">Vegan</span>
</div>
```
