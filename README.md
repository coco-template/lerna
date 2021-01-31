# lerna

yet, speed mono repo management with a few requirements.

## Arrangement

- mono repo should have identical commit message flavor, restrict at root level
- mono repo should have similar lint rules, restrict at root level, override within own package
- mono repo may have totally different target environments, aka browser compatibility requirement, declare within own package in package.json file
- typescript recognize require pretty path mappings

## Usage

```shell
# unit test
npm run test;

# production compile
npm run build;
```

## Contact

hjj491229492@hotmail.com

## License

MIT
