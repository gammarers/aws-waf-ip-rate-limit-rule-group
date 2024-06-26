# API Reference <a name="API Reference" id="api-reference"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### WafIpRateLimitRuleGroup <a name="WafIpRateLimitRuleGroup" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup"></a>

#### Initializers <a name="Initializers" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.Initializer"></a>

```typescript
import { WafIpRateLimitRuleGroup } from '@gammarers/aws-waf-ip-rate-limit-rule-group'

new WafIpRateLimitRuleGroup(scope: Construct, id: string, props: WafIpRateLimitRuleGroupProps)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | Specifies whether this is for an Amazon CloudFront distribution or for a regional application. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.Initializer.parameter.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.Initializer.parameter.props">props</a></code> | <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps">WafIpRateLimitRuleGroupProps</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

Specifies whether this is for an Amazon CloudFront distribution or for a regional application.

A regional application can be an Application Load Balancer (ALB), an Amazon API Gateway REST API, an AWS AppSync GraphQL API, an Amazon Cognito user pool, or an AWS App Runner service. Valid Values are `CLOUDFRONT` and `REGIONAL` .

> For `CLOUDFRONT` , you must create your WAFv2 resources in the US East (N. Virginia) Region, `us-east-1` .

---

##### `id`<sup>Required</sup> <a name="id" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.Initializer.parameter.id"></a>

- *Type:* string

---

##### `props`<sup>Required</sup> <a name="props" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.Initializer.parameter.props"></a>

- *Type:* <a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps">WafIpRateLimitRuleGroupProps</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDeletionOverride">addDeletionOverride</a></code> | Syntactic sugar for `addOverride(path, undefined)`. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDependency">addDependency</a></code> | Indicates that this resource depends on another resource and cannot be provisioned unless the other resource has been successfully provisioned. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDependsOn">addDependsOn</a></code> | Indicates that this resource depends on another resource and cannot be provisioned unless the other resource has been successfully provisioned. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addMetadata">addMetadata</a></code> | Add a value to the CloudFormation Resource Metadata. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addOverride">addOverride</a></code> | Adds an override to the synthesized CloudFormation resource. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addPropertyDeletionOverride">addPropertyDeletionOverride</a></code> | Adds an override that deletes the value of a property from the resource definition. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addPropertyOverride">addPropertyOverride</a></code> | Adds an override to a resource property. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.applyRemovalPolicy">applyRemovalPolicy</a></code> | Sets the deletion policy of the resource based on the removal policy specified. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.getAtt">getAtt</a></code> | Returns a token for an runtime attribute of this resource. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.getMetadata">getMetadata</a></code> | Retrieve a value value from the CloudFormation Resource Metadata. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.obtainDependencies">obtainDependencies</a></code> | Retrieves an array of resources this resource depends on. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.obtainResourceDependencies">obtainResourceDependencies</a></code> | Get a shallow copy of dependencies between this resource and other resources in the same stack. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.removeDependency">removeDependency</a></code> | Indicates that this resource no longer depends on another resource. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.replaceDependency">replaceDependency</a></code> | Replaces one dependency with another. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.inspect">inspect</a></code> | Examines the CloudFormation resource and discloses attributes. |

---

##### `toString` <a name="toString" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `overrideLogicalId` <a name="overrideLogicalId" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `addDeletionOverride` <a name="addDeletionOverride" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDeletionOverride"></a>

```typescript
public addDeletionOverride(path: string): void
```

Syntactic sugar for `addOverride(path, undefined)`.

###### `path`<sup>Required</sup> <a name="path" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDeletionOverride.parameter.path"></a>

- *Type:* string

The path of the value to delete.

---

##### `addDependency` <a name="addDependency" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDependency"></a>

```typescript
public addDependency(target: CfnResource): void
```

Indicates that this resource depends on another resource and cannot be provisioned unless the other resource has been successfully provisioned.

This can be used for resources across stacks (or nested stack) boundaries
and the dependency will automatically be transferred to the relevant scope.

###### `target`<sup>Required</sup> <a name="target" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDependency.parameter.target"></a>

- *Type:* aws-cdk-lib.CfnResource

---

##### ~~`addDependsOn`~~ <a name="addDependsOn" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDependsOn"></a>

```typescript
public addDependsOn(target: CfnResource): void
```

Indicates that this resource depends on another resource and cannot be provisioned unless the other resource has been successfully provisioned.

###### `target`<sup>Required</sup> <a name="target" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addDependsOn.parameter.target"></a>

- *Type:* aws-cdk-lib.CfnResource

---

##### `addMetadata` <a name="addMetadata" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addMetadata"></a>

```typescript
public addMetadata(key: string, value: any): void
```

Add a value to the CloudFormation Resource Metadata.

> [https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/metadata-section-structure.html

Note that this is a different set of metadata from CDK node metadata; this
metadata ends up in the stack template under the resource, whereas CDK
node metadata ends up in the Cloud Assembly.](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/metadata-section-structure.html

Note that this is a different set of metadata from CDK node metadata; this
metadata ends up in the stack template under the resource, whereas CDK
node metadata ends up in the Cloud Assembly.)

###### `key`<sup>Required</sup> <a name="key" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addMetadata.parameter.key"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addMetadata.parameter.value"></a>

- *Type:* any

---

##### `addOverride` <a name="addOverride" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

Adds an override to the synthesized CloudFormation resource.

To add a
property override, either use `addPropertyOverride` or prefix `path` with
"Properties." (i.e. `Properties.TopicName`).

If the override is nested, separate each nested level using a dot (.) in the path parameter.
If there is an array as part of the nesting, specify the index in the path.

To include a literal `.` in the property name, prefix with a `\`. In most
programming languages you will need to write this as `"\\."` because the
`\` itself will need to be escaped.

For example,
```typescript
cfnResource.addOverride('Properties.GlobalSecondaryIndexes.0.Projection.NonKeyAttributes', ['myattribute']);
cfnResource.addOverride('Properties.GlobalSecondaryIndexes.1.ProjectionType', 'INCLUDE');
```
would add the overrides
```json
"Properties": {
  "GlobalSecondaryIndexes": [
    {
      "Projection": {
        "NonKeyAttributes": [ "myattribute" ]
        ...
      }
      ...
    },
    {
      "ProjectionType": "INCLUDE"
      ...
    },
  ]
  ...
}
```

The `value` argument to `addOverride` will not be processed or translated
in any way. Pass raw JSON values in here with the correct capitalization
for CloudFormation. If you pass CDK classes or structs, they will be
rendered with lowercased key names, and CloudFormation will reject the
template.

###### `path`<sup>Required</sup> <a name="path" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addOverride.parameter.path"></a>

- *Type:* string

The path of the property, you can use dot notation to override values in complex types.

Any intermediate keys
will be created as needed.

---

###### `value`<sup>Required</sup> <a name="value" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addOverride.parameter.value"></a>

- *Type:* any

The value.

Could be primitive or complex.

---

##### `addPropertyDeletionOverride` <a name="addPropertyDeletionOverride" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addPropertyDeletionOverride"></a>

```typescript
public addPropertyDeletionOverride(propertyPath: string): void
```

Adds an override that deletes the value of a property from the resource definition.

###### `propertyPath`<sup>Required</sup> <a name="propertyPath" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addPropertyDeletionOverride.parameter.propertyPath"></a>

- *Type:* string

The path to the property.

---

##### `addPropertyOverride` <a name="addPropertyOverride" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addPropertyOverride"></a>

```typescript
public addPropertyOverride(propertyPath: string, value: any): void
```

Adds an override to a resource property.

Syntactic sugar for `addOverride("Properties.<...>", value)`.

###### `propertyPath`<sup>Required</sup> <a name="propertyPath" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addPropertyOverride.parameter.propertyPath"></a>

- *Type:* string

The path of the property.

---

###### `value`<sup>Required</sup> <a name="value" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.addPropertyOverride.parameter.value"></a>

- *Type:* any

The value.

---

##### `applyRemovalPolicy` <a name="applyRemovalPolicy" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.applyRemovalPolicy"></a>

```typescript
public applyRemovalPolicy(policy?: RemovalPolicy, options?: RemovalPolicyOptions): void
```

Sets the deletion policy of the resource based on the removal policy specified.

The Removal Policy controls what happens to this resource when it stops
being managed by CloudFormation, either because you've removed it from the
CDK application or because you've made a change that requires the resource
to be replaced.

The resource can be deleted (`RemovalPolicy.DESTROY`), or left in your AWS
account for data recovery and cleanup later (`RemovalPolicy.RETAIN`). In some
cases, a snapshot can be taken of the resource prior to deletion
(`RemovalPolicy.SNAPSHOT`). A list of resources that support this policy
can be found in the following link:

> [https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-deletionpolicy.html#aws-attribute-deletionpolicy-options](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-deletionpolicy.html#aws-attribute-deletionpolicy-options)

###### `policy`<sup>Optional</sup> <a name="policy" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.applyRemovalPolicy.parameter.policy"></a>

- *Type:* aws-cdk-lib.RemovalPolicy

---

###### `options`<sup>Optional</sup> <a name="options" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.applyRemovalPolicy.parameter.options"></a>

- *Type:* aws-cdk-lib.RemovalPolicyOptions

---

##### `getAtt` <a name="getAtt" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.getAtt"></a>

```typescript
public getAtt(attributeName: string, typeHint?: ResolutionTypeHint): Reference
```

Returns a token for an runtime attribute of this resource.

Ideally, use generated attribute accessors (e.g. `resource.arn`), but this can be used for future compatibility
in case there is no generated attribute.

###### `attributeName`<sup>Required</sup> <a name="attributeName" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.getAtt.parameter.attributeName"></a>

- *Type:* string

The name of the attribute.

---

###### `typeHint`<sup>Optional</sup> <a name="typeHint" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.getAtt.parameter.typeHint"></a>

- *Type:* aws-cdk-lib.ResolutionTypeHint

---

##### `getMetadata` <a name="getMetadata" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.getMetadata"></a>

```typescript
public getMetadata(key: string): any
```

Retrieve a value value from the CloudFormation Resource Metadata.

> [https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/metadata-section-structure.html

Note that this is a different set of metadata from CDK node metadata; this
metadata ends up in the stack template under the resource, whereas CDK
node metadata ends up in the Cloud Assembly.](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/metadata-section-structure.html

Note that this is a different set of metadata from CDK node metadata; this
metadata ends up in the stack template under the resource, whereas CDK
node metadata ends up in the Cloud Assembly.)

###### `key`<sup>Required</sup> <a name="key" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.getMetadata.parameter.key"></a>

- *Type:* string

---

##### `obtainDependencies` <a name="obtainDependencies" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.obtainDependencies"></a>

```typescript
public obtainDependencies(): Stack | CfnResource[]
```

Retrieves an array of resources this resource depends on.

This assembles dependencies on resources across stacks (including nested stacks)
automatically.

##### `obtainResourceDependencies` <a name="obtainResourceDependencies" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.obtainResourceDependencies"></a>

```typescript
public obtainResourceDependencies(): CfnResource[]
```

Get a shallow copy of dependencies between this resource and other resources in the same stack.

##### `removeDependency` <a name="removeDependency" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.removeDependency"></a>

```typescript
public removeDependency(target: CfnResource): void
```

Indicates that this resource no longer depends on another resource.

This can be used for resources across stacks (including nested stacks)
and the dependency will automatically be removed from the relevant scope.

###### `target`<sup>Required</sup> <a name="target" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.removeDependency.parameter.target"></a>

- *Type:* aws-cdk-lib.CfnResource

---

##### `replaceDependency` <a name="replaceDependency" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.replaceDependency"></a>

```typescript
public replaceDependency(target: CfnResource, newTarget: CfnResource): void
```

Replaces one dependency with another.

###### `target`<sup>Required</sup> <a name="target" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.replaceDependency.parameter.target"></a>

- *Type:* aws-cdk-lib.CfnResource

The dependency to replace.

---

###### `newTarget`<sup>Required</sup> <a name="newTarget" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.replaceDependency.parameter.newTarget"></a>

- *Type:* aws-cdk-lib.CfnResource

The new dependency to add.

---

##### `inspect` <a name="inspect" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.inspect"></a>

```typescript
public inspect(inspector: TreeInspector): void
```

Examines the CloudFormation resource and discloses attributes.

###### `inspector`<sup>Required</sup> <a name="inspector" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.inspect.parameter.inspector"></a>

- *Type:* aws-cdk-lib.TreeInspector

tree inspector to collect and process attributes.

---

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isCfnElement">isCfnElement</a></code> | Returns `true` if a construct is a stack element (i.e. part of the synthesized cloudformation template). |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isCfnResource">isCfnResource</a></code> | Check whether the given construct is a CfnResource. |

---

##### ~~`isConstruct`~~ <a name="isConstruct" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isConstruct"></a>

```typescript
import { WafIpRateLimitRuleGroup } from '@gammarers/aws-waf-ip-rate-limit-rule-group'

WafIpRateLimitRuleGroup.isConstruct(x: any)
```

Checks if `x` is a construct.

###### `x`<sup>Required</sup> <a name="x" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isCfnElement` <a name="isCfnElement" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isCfnElement"></a>

```typescript
import { WafIpRateLimitRuleGroup } from '@gammarers/aws-waf-ip-rate-limit-rule-group'

WafIpRateLimitRuleGroup.isCfnElement(x: any)
```

Returns `true` if a construct is a stack element (i.e. part of the synthesized cloudformation template).

Uses duck-typing instead of `instanceof` to allow stack elements from different
versions of this library to be included in the same stack.

###### `x`<sup>Required</sup> <a name="x" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isCfnElement.parameter.x"></a>

- *Type:* any

---

##### `isCfnResource` <a name="isCfnResource" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isCfnResource"></a>

```typescript
import { WafIpRateLimitRuleGroup } from '@gammarers/aws-waf-ip-rate-limit-rule-group'

WafIpRateLimitRuleGroup.isCfnResource(construct: IConstruct)
```

Check whether the given construct is a CfnResource.

###### `construct`<sup>Required</sup> <a name="construct" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.isCfnResource.parameter.construct"></a>

- *Type:* constructs.IConstruct

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.creationStack">creationStack</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.logicalId">logicalId</a></code> | <code>string</code> | The logical ID for this CloudFormation stack element. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.stack">stack</a></code> | <code>aws-cdk-lib.Stack</code> | The stack in which this element is defined. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.ref">ref</a></code> | <code>string</code> | Return a string that will be resolved to a CloudFormation `{ Ref }` for this element. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.cfnOptions">cfnOptions</a></code> | <code>aws-cdk-lib.ICfnResourceOptions</code> | Options for this resource, such as condition, update policy etc. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.cfnResourceType">cfnResourceType</a></code> | <code>string</code> | AWS resource type. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.attrArn">attrArn</a></code> | <code>string</code> | The Amazon Resource Name (ARN) of the rule group. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.attrId">attrId</a></code> | <code>string</code> | The ID of the rule group. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.attrLabelNamespace">attrLabelNamespace</a></code> | <code>string</code> | The label namespace prefix for this rule group. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.tags">tags</a></code> | <code>aws-cdk-lib.TagManager</code> | Key:value pairs associated with an AWS resource. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.capacity">capacity</a></code> | <code>number</code> | The web ACL capacity units (WCUs) required for this rule group. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.scope">scope</a></code> | <code>string</code> | Specifies whether this is for an Amazon CloudFront distribution or for a regional application. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.visibilityConfig">visibilityConfig</a></code> | <code>aws-cdk-lib.IResolvable \| aws-cdk-lib.aws_wafv2.CfnRuleGroup.VisibilityConfigProperty</code> | Defines and enables Amazon CloudWatch metrics and web request sample collection. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.availableLabels">availableLabels</a></code> | <code>aws-cdk-lib.IResolvable \| aws-cdk-lib.IResolvable \| aws-cdk-lib.aws_wafv2.CfnRuleGroup.LabelSummaryProperty[]</code> | The labels that one or more rules in this rule group add to matching web requests. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.consumedLabels">consumedLabels</a></code> | <code>aws-cdk-lib.IResolvable \| aws-cdk-lib.IResolvable \| aws-cdk-lib.aws_wafv2.CfnRuleGroup.LabelSummaryProperty[]</code> | The labels that one or more rules in this rule group match against in label match statements. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.customResponseBodies">customResponseBodies</a></code> | <code>aws-cdk-lib.IResolvable \| {[ key: string ]: aws-cdk-lib.IResolvable \| aws-cdk-lib.aws_wafv2.CfnRuleGroup.CustomResponseBodyProperty}</code> | A map of custom response keys and content bodies. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.description">description</a></code> | <code>string</code> | A description of the rule group that helps with identification. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.name">name</a></code> | <code>string</code> | The name of the rule group. |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.rules">rules</a></code> | <code>aws-cdk-lib.IResolvable \| aws-cdk-lib.IResolvable \| aws-cdk-lib.aws_wafv2.CfnRuleGroup.RuleProperty[]</code> | The rule statements used to identify the web requests that you want to allow, block, or count. |

---

##### `node`<sup>Required</sup> <a name="node" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

---

##### `logicalId`<sup>Required</sup> <a name="logicalId" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.logicalId"></a>

```typescript
public readonly logicalId: string;
```

- *Type:* string

The logical ID for this CloudFormation stack element.

The logical ID of the element
is calculated from the path of the resource node in the construct tree.

To override this value, use `overrideLogicalId(newLogicalId)`.

---

##### `stack`<sup>Required</sup> <a name="stack" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.stack"></a>

```typescript
public readonly stack: Stack;
```

- *Type:* aws-cdk-lib.Stack

The stack in which this element is defined.

CfnElements must be defined within a stack scope (directly or indirectly).

---

##### `ref`<sup>Required</sup> <a name="ref" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.ref"></a>

```typescript
public readonly ref: string;
```

- *Type:* string

Return a string that will be resolved to a CloudFormation `{ Ref }` for this element.

If, by any chance, the intrinsic reference of a resource is not a string, you could
coerce it to an IResolvable through `Lazy.any({ produce: resource.ref })`.

---

##### `cfnOptions`<sup>Required</sup> <a name="cfnOptions" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.cfnOptions"></a>

```typescript
public readonly cfnOptions: ICfnResourceOptions;
```

- *Type:* aws-cdk-lib.ICfnResourceOptions

Options for this resource, such as condition, update policy etc.

---

##### `cfnResourceType`<sup>Required</sup> <a name="cfnResourceType" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.cfnResourceType"></a>

```typescript
public readonly cfnResourceType: string;
```

- *Type:* string

AWS resource type.

---

##### `attrArn`<sup>Required</sup> <a name="attrArn" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.attrArn"></a>

```typescript
public readonly attrArn: string;
```

- *Type:* string

The Amazon Resource Name (ARN) of the rule group.

---

##### `attrId`<sup>Required</sup> <a name="attrId" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.attrId"></a>

```typescript
public readonly attrId: string;
```

- *Type:* string

The ID of the rule group.

---

##### `attrLabelNamespace`<sup>Required</sup> <a name="attrLabelNamespace" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.attrLabelNamespace"></a>

```typescript
public readonly attrLabelNamespace: string;
```

- *Type:* string

The label namespace prefix for this rule group.

All labels added by rules in this rule group have this prefix.

The syntax for the label namespace prefix for a rule group is the following: `awswaf:<account ID>:rule group:<rule group name>:`

When a rule with a label matches a web request, AWS WAF adds the fully qualified label to the request. A fully qualified label is made up of the label namespace from the rule group or web ACL where the rule is defined and the label from the rule, separated by a colon.

---

##### `tags`<sup>Required</sup> <a name="tags" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.tags"></a>

```typescript
public readonly tags: TagManager;
```

- *Type:* aws-cdk-lib.TagManager

Key:value pairs associated with an AWS resource.

The key:value pair can be anything you define. Typically, the tag key represents a category (such as "environment") and the tag value represents a specific value within that category (such as "test," "development," or "production"). You can add up to 50 tags to each AWS resource.

> To modify tags on existing resources, use the AWS WAF APIs or command line interface. With AWS CloudFormation , you can only add tags to AWS WAF resources during resource creation.

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-tags](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-tags)

---

##### `capacity`<sup>Required</sup> <a name="capacity" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.capacity"></a>

```typescript
public readonly capacity: number;
```

- *Type:* number

The web ACL capacity units (WCUs) required for this rule group.

When you create your own rule group, you define this, and you cannot change it after creation. When you add or modify the rules in a rule group, AWS WAF enforces this limit.

AWS WAF uses WCUs to calculate and control the operating resources that are used to run your rules, rule groups, and web ACLs. AWS WAF calculates capacity differently for each rule type, to reflect the relative cost of each rule. Simple rules that cost little to run use fewer WCUs than more complex rules that use more processing power. Rule group capacity is fixed at creation, which helps users plan their web ACL WCU usage when they use a rule group. The WCU limit for web ACLs is 1,500.

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-capacity](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-capacity)

---

##### `scope`<sup>Required</sup> <a name="scope" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.scope"></a>

```typescript
public readonly scope: string;
```

- *Type:* string

Specifies whether this is for an Amazon CloudFront distribution or for a regional application.

A regional application can be an Application Load Balancer (ALB), an Amazon API Gateway REST API, an AWS AppSync GraphQL API, an Amazon Cognito user pool, or an AWS App Runner service. Valid Values are `CLOUDFRONT` and `REGIONAL` .

> For `CLOUDFRONT` , you must create your WAFv2 resources in the US East (N. Virginia) Region, `us-east-1` .

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-scope](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-scope)

---

##### `visibilityConfig`<sup>Required</sup> <a name="visibilityConfig" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.visibilityConfig"></a>

```typescript
public readonly visibilityConfig: IResolvable | VisibilityConfigProperty;
```

- *Type:* aws-cdk-lib.IResolvable | aws-cdk-lib.aws_wafv2.CfnRuleGroup.VisibilityConfigProperty

Defines and enables Amazon CloudWatch metrics and web request sample collection.

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-visibilityconfig](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-visibilityconfig)

---

##### `availableLabels`<sup>Optional</sup> <a name="availableLabels" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.availableLabels"></a>

```typescript
public readonly availableLabels: IResolvable | IResolvable | LabelSummaryProperty[];
```

- *Type:* aws-cdk-lib.IResolvable | aws-cdk-lib.IResolvable | aws-cdk-lib.aws_wafv2.CfnRuleGroup.LabelSummaryProperty[]

The labels that one or more rules in this rule group add to matching web requests.

These labels are defined in the `RuleLabels` for a `Rule` .

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-availablelabels](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-availablelabels)

---

##### `consumedLabels`<sup>Optional</sup> <a name="consumedLabels" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.consumedLabels"></a>

```typescript
public readonly consumedLabels: IResolvable | IResolvable | LabelSummaryProperty[];
```

- *Type:* aws-cdk-lib.IResolvable | aws-cdk-lib.IResolvable | aws-cdk-lib.aws_wafv2.CfnRuleGroup.LabelSummaryProperty[]

The labels that one or more rules in this rule group match against in label match statements.

These labels are defined in a `LabelMatchStatement` specification, in the `Statement` definition of a rule.

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-consumedlabels](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-consumedlabels)

---

##### `customResponseBodies`<sup>Optional</sup> <a name="customResponseBodies" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.customResponseBodies"></a>

```typescript
public readonly customResponseBodies: IResolvable | {[ key: string ]: IResolvable | CustomResponseBodyProperty};
```

- *Type:* aws-cdk-lib.IResolvable | {[ key: string ]: aws-cdk-lib.IResolvable | aws-cdk-lib.aws_wafv2.CfnRuleGroup.CustomResponseBodyProperty}

A map of custom response keys and content bodies.

When you create a rule with a block action, you can send a custom response to the web request. You define these for the rule group, and then use them in the rules that you define in the rule group.

For information about customizing web requests and responses, see [Customizing web requests and responses in AWS WAF](https://docs.aws.amazon.com/waf/latest/developerguide/waf-custom-request-response.html) in the *AWS WAF Developer Guide* .

For information about the limits on count and size for custom request and response settings, see [AWS WAF quotas](https://docs.aws.amazon.com/waf/latest/developerguide/limits.html) in the *AWS WAF Developer Guide* .

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-customresponsebodies](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-customresponsebodies)

---

##### `description`<sup>Optional</sup> <a name="description" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

A description of the rule group that helps with identification.

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-description](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-description)

---

##### `name`<sup>Optional</sup> <a name="name" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

The name of the rule group.

You cannot change the name of a rule group after you create it.

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-name](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-name)

---

##### `rules`<sup>Optional</sup> <a name="rules" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.rules"></a>

```typescript
public readonly rules: IResolvable | IResolvable | RuleProperty[];
```

- *Type:* aws-cdk-lib.IResolvable | aws-cdk-lib.IResolvable | aws-cdk-lib.aws_wafv2.CfnRuleGroup.RuleProperty[]

The rule statements used to identify the web requests that you want to allow, block, or count.

Each rule includes one top-level statement that AWS WAF uses to identify matching web requests, and parameters that govern how AWS WAF handles them.

> [http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-rules](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-rulegroup.html#cfn-wafv2-rulegroup-rules)

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.CFN_RESOURCE_TYPE_NAME">CFN_RESOURCE_TYPE_NAME</a></code> | <code>string</code> | The CloudFormation resource type name for this resource class. |

---

##### `CFN_RESOURCE_TYPE_NAME`<sup>Required</sup> <a name="CFN_RESOURCE_TYPE_NAME" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroup.property.CFN_RESOURCE_TYPE_NAME"></a>

```typescript
public readonly CFN_RESOURCE_TYPE_NAME: string;
```

- *Type:* string

The CloudFormation resource type name for this resource class.

---

## Structs <a name="Structs" id="Structs"></a>

### WafIpRateLimitRuleGroupProps <a name="WafIpRateLimitRuleGroupProps" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps"></a>

#### Initializer <a name="Initializer" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps.Initializer"></a>

```typescript
import { WafIpRateLimitRuleGroupProps } from '@gammarers/aws-waf-ip-rate-limit-rule-group'

const wafIpRateLimitRuleGroupProps: WafIpRateLimitRuleGroupProps = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps.property.scope">scope</a></code> | <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.Scope">Scope</a></code> | *No description.* |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps.property.rateLimitCount">rateLimitCount</a></code> | <code>number</code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps.property.scope"></a>

```typescript
public readonly scope: Scope;
```

- *Type:* <a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.Scope">Scope</a>

---

##### `name`<sup>Optional</sup> <a name="name" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `rateLimitCount`<sup>Optional</sup> <a name="rateLimitCount" id="@gammarers/aws-waf-ip-rate-limit-rule-group.WafIpRateLimitRuleGroupProps.property.rateLimitCount"></a>

```typescript
public readonly rateLimitCount: number;
```

- *Type:* number

---



## Enums <a name="Enums" id="Enums"></a>

### Scope <a name="Scope" id="@gammarers/aws-waf-ip-rate-limit-rule-group.Scope"></a>

#### Members <a name="Members" id="Members"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.Scope.GLOBAL">GLOBAL</a></code> | *No description.* |
| <code><a href="#@gammarers/aws-waf-ip-rate-limit-rule-group.Scope.REGIONAL">REGIONAL</a></code> | *No description.* |

---

##### `GLOBAL` <a name="GLOBAL" id="@gammarers/aws-waf-ip-rate-limit-rule-group.Scope.GLOBAL"></a>

---


##### `REGIONAL` <a name="REGIONAL" id="@gammarers/aws-waf-ip-rate-limit-rule-group.Scope.REGIONAL"></a>

---

