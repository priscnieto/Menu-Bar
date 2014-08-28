#navbar{
	width:200px;
	}

#menubar, #menubar ul
{
    border: 2px solid #000000;
    list-style-type: none;
    padding: 0 0 28px 10px;
    margin: 0;
}
#menubar li
{
    float: left;
    position: relative;
    margin-right: 3px;
    border-bottom: 1px solid #000000;
}
#menubar ul
{
    position: absolute;
    top: 28px;
    width: 100px;
    padding: 0;
    display: none;
}
#menubar ul li
{
    float:none;
    margin: 0;
    padding-left: 10px;
    line-height: 20px;
}
#menubar a:link, #menubar a:visited
{
    display: block;
    text-align: left;
    text-decoration: none;
    padding: 5px;
}
#menubar li:hover
{
    background-color: #BDBDBD;
}
#menubar li:hover ul
{
    display: block;
}
