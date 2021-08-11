# Buttons

Web-ui-components include predefined button styles, each serving its own semantic purpose, with a few extras thrown in for more control.

## Usage

`<Button className="button--default" type="button"
 onClick={onClickHandler}>
    Text
</Button>`


## Available classNames for Buttons:

- ```button--primary``` <Button type="button" style="background: linear-gradient(#1a237e, #0b1259); color: #fff; padding: 10px 16px; border-radius: 30px; border: none">
   Primary 
</Button>

- ```button--secondary``` <Button type="button" style="background: linear-gradient(#ff5722, #E84E1D); color: #fff; padding: 10px 16px; border-radius: 30px; border: none">
   Secondary 
</Button>


- ```button--default``` <Button type="button" style="background: linear-gradient(#828282, #6d6d6d); color: #fff; padding: 10px 16px; border-radius: 30px; border: none">
   Default 
</Button>


- ```button--danger``` <Button type="button" style="background: linear-gradient(#A83131, #8d2929); color: #fff; padding: 10px 16px; border-radius: 30px; border: none">
   Danger 
</Button>

- ```button--info```
<Button type="button" style="background: #E2E2E2; color: #414042; padding: 10px 16px; border-radius: 3px; border: none; width: 150px;text-align: left">
   Default 
</Button>


- ```button--round```  <Button type="button" style="background: #2aad45; color: #fff; padding: 4px 12px; border-radius: 50%; border: none; font-size: 24px; font-weight: 700"> + </Button>

- ```button--icon``` <Button 
  style="background-color: #414042;
    padding: 2px; color: #fff; padding: 8px 12px; border-radius: 3px; border: none">
<svg style="width: 20px; height: 20px;" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="expand" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="svg-inline--fa fa-expand fa-w-14 fa-2x"><path fill="currentColor" d="M0 180V56c0-13.3 10.7-24 24-24h124c6.6 0 12 5.4 12 12v40c0 6.6-5.4 12-12 12H64v84c0 6.6-5.4 12-12 12H12c-6.6 0-12-5.4-12-12zM288 44v40c0 6.6 5.4 12 12 12h84v84c0 6.6 5.4 12 12 12h40c6.6 0 12-5.4 12-12V56c0-13.3-10.7-24-24-24H300c-6.6 0-12 5.4-12 12zm148 276h-40c-6.6 0-12 5.4-12 12v84h-84c-6.6 0-12 5.4-12 12v40c0 6.6 5.4 12 12 12h124c13.3 0 24-10.7 24-24V332c0-6.6-5.4-12-12-12zM160 468v-40c0-6.6-5.4-12-12-12H64v-84c0-6.6-5.4-12-12-12H12c-6.6 0-12 5.4-12 12v124c0 13.3 10.7 24 24 24h124c6.6 0 12-5.4 12-12z" class=""></path></svg>
</Button> (note, the `icon` included to `Button` component)


> <Button 
  className="button--icon"
  onClick={() => expandHanler}
  type="button">
>>  <FontAwesomeIcon className="expand" icon={Expand} size="2x" />`
> </Button>`


## Disabled state
Make buttons look inactive by adding the `disabled` boolean attribute to any `<Button>` element.

```
<Button className="button--secondary" type="submit" disabled>
Disabled button            
</Button>```