# JetForm Builder Column Gap Mobile Fix  

This repository contains a simple CSS fix for JetForm Builder's column gap issue on mobile devices. The provided CSS targets screens with a maximum width of 768px and adjusts the padding and margin of JetForm Builder columns to improve mobile layout.  

## CSS Code  
The following CSS code resolves the column gap issue for JetForm Builder on mobile devices:  

```css  
@media (max-width: 768px) {  
    .jet-form-builder .wp-block-column {  
        padding: 0 !important;  
        margin: 0 !important;  
    }  
}  
