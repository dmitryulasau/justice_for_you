# Justice For You Law Firm

Dmitry, Giovanni, and Andre created a mock-up website for "Justice For You Law Firm". We've used HTML, CSS, and Bootstrap to create a detailed mock-up of the homework assignment. 

## Individual Responsibilities
We thought it would be beneficial to have one person work on the header, footer, and navigation bar since they're identical on each page, while the other two team members could start working on the other pages. Here's how we organized our work assignments:

### Dmitry:
- Manage main GitHub repository 
- Navigation bar
- Header
- Footer
- Additional CSS touch-ups

### Andre:
- Page 2
- README file

### Giovanni:
- Page 3
- Page 4


## Additional Features
### Hoverable Drop-Down

Moving your mouse over the "Login" button displays a login option for any user visiting "Justice For You".

```
HTML

<!-- LOGIN & PASSWORD -->
<form>
<div class="mb-3">
    <label for="user-email" class="form-label"
    >Email address:</label
    >
    <input
    type="email"
    class="form-control"
    id="user-email"
    />
</div>

<div class="mb-3">
    <label for="user-password" class="form-label"
    >Password:</label
    >
    <input
    type="password"
    class="form-control"
    id="user-password"
    />
</div>
<div class="buttons">
    <button type="submit" class="btn btn-primary">
    TO JUSTICE
    </button>

    <a href="#" class="sign-in"><span>Sign In</span></a>
</div>
</form>
<!-- LOGIN & PASSWORD END-->
```
CSS
```
CSS
/* DROPDOWN */
.dropdown {
  /* position: relative; */
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #d2ba6f;
  min-width: 160px;
  box-shadow: 0px 4px 8px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  right: 0;
  padding: 10px;
  border-radius: 7px;
}

.dropdown:hover .dropdown-content {
  display: block;
}

input {
  width: 50%;
}

input[type="email"],
input[type="password"] {
  width: 100%;
  padding: 0;
  margin: 0;
}

input[type="email"]:focus,
input[type="password"]:focus {
  border-color: #923530;
  box-shadow: 0 0 6px 4px rgb(146 53 38 / 50%);
  outline: none;
}

.btn-primary {
  border: none;
  background-color: var(--red);
  font-weight: 600;
}

.btn-primary:hover {
  border: none;
  background-color: var(--red);
  color: #d2ba6f;
}

form {
  width: 180px;
}

.buttons {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

```

## Feedback
Any feedback on this project is greatly appreciated. 

Please send questions or comments to [Andre](mailto:aalonardo@gmail.com).


## License
[MIT](https://choosealicense.com/licenses/mit/)